//input- n for dimensions n x n of wordsearch & words to be found separated by commas
//output- 2d array of randomly generated inputed words in wordsearch format
import java.util.Scanner;
import java.util.Arrays;

public class WordSearchGenerator {
    char[][] wordSearch;
    int s;
    int sizeOfArr;
    String[] words;
    public static final int [][] DIRECTIONS = { 
        {1,0}, {0,1}, {1,1}, {1,-1}, {-1, 0}, {0, -1}, {-1, -1}, {-1, 1}
    }

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.println("Input your preferred size for the Wordsearch(n x n): ");
        int sizeOfArr = scan.nextInt();
        System.out.println("How many words would you like to hide in your Wordsearch?");
        int numWords = scan.nextInt();
        String[] wordArr = new String[numWords];
        for (int i = 0; i < numWords; i++) {
            System.out.println("What word would would you like to hide?");
            wordArr[i] = scan.next();
        }
        WordSearchGenerator wordSearch = new WordSearchGenerator(sizeOfArr, wordArr);
        System.out.println()//print nested array
        char[][] solution = WordSearchGenerator.wordSearchSolver(wordSearch, wordArr);
        System.out.println("Type 'Yes' when you would like to see the solution")
        if(scan.next() == "Yes") {
            //SOP oution
        }

        // System.out.println(Arrays.toString(wordArr));
        scan.close();
    }

    public WordSearchGenerator() {
        wordSearch={};
        sizeOfArr = 0;

    }

    public WordSearchGenerator(int size, String[] wordArr) {
        s = size;
        sizeOfArr = n * n;
        words = wordArr;
        wordSearch = new char[n][n];

    }

    public static char[][] wordSearchSolver(WordSearchGenerator wordSearchtoSolve, String[] wordstoFind){
        return {{0, 0}}
    }
}