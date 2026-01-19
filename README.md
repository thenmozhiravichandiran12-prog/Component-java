public class StringExample {
    public static void main(String[] args) {
        String username = "JohnDoe123";

        // Extract first 3 characters
        String firstThree = username.substring(0, 3);
        System.out.println(firstThree);

        // Extract first 5 characters
        String firstFive = username.substring(0, 5);
        System.out.println(firstFive);

        // Handle short string safely
        String shortName = "Hi";
        String firstThreeShort = shortName.substring(0, Math.min(3, shortName.length()));
        System.out.println(firstThreeShort);
    }
}
