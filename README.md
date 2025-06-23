CODE : 

import java.util.Random;

public class QuoteGenerator {
    public static void main(String[] args) {
        String[] quotes = {
            "Believe you can and you're halfway there. - Theodore Roosevelt",
            "The only way to do great work is to love what you do. - Steve Jobs",
            "Success is not final, failure is not fatal: It is the courage to continue that counts. - Winston Churchill"
        };

        Random random = new Random();
        int index = random.nextInt(quotes.length);

        System.out.println("Quote of the day:");
        System.out.println(quotes[index]);
    }
}





OUTPUT: 
Quote of the day:
The only way to do great work is to love what you do. - Steve Jobs

=== Code Execution Successful ===