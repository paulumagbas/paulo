using System;

class TravelDestinations {
    static void Main(string[] args) {
        Console.WriteLine("Where do you like to travel?:\n");
        
        Console.WriteLine("1. Beach");
        Console.WriteLine("2. National Park");
        Console.WriteLine("3. City");
        Console.WriteLine("4. Historical Landmark");
        
        Console.WriteLine("\nEnter the number of a destination to learn more: ");
        
        int choice = Convert.ToInt32(Console.ReadLine());
        
        switch (choice) {
            case 1:
            Console.WriteLine("\nHere are the list of beaches to travel: ");
            Console.WriteLine("1. Boracay, Philippines");
            Console.WriteLine("2. Maldives");
            Console.WriteLine("3. Palawan, Philippines");
            
            Console.WriteLine("\nEnter a number to see the description: ");
            
            int innerChoice = Convert.ToInt32(Console.ReadLine());
            
            switch (innerChoice) {
                case 1:
                Console.WriteLine(" Boracay is a small island located in the central Philippines, famous for its pristine white sandy beaches and crystal-clear waters. It is a popular destination for travelers from all over the world, offering a perfect mix of relaxation, adventure and nightlife. ");
                break;
                case 2:
                Console.WriteLine(" Maldives is a tropical paradise known for its stunning beaches and crystal-clear waters. The beaches in the Maldives are characterized by soft white sand, clear turquoise waters, and an abundance of marine life, making it a perfect destination for snorkeling and diving. ");
                break;
                case 3:
                Console.WriteLine(" Palawan is a province located in the western part of the Philippines, known for its stunning natural beauty and pristine beaches. One of the most famous beaches in Palawan is the aptly named El Nido, which is characterized by its powdery white sand, crystal-clear waters, and towering limestone cliffs. ");
                return;
                default:
                Console.WriteLine("Invalid choice.");
                break;
            }
            break;
            case 2:
            Console.WriteLine("\nHere are the list of national parks to travel: ");
            Console.WriteLine("1. Yellowstone National Park, USA");
            Console.WriteLine("2. Banff National Park, Canada");
            Console.WriteLine("3. Plitvice Lakes National Park, Croatia");
            
            Console.WriteLine("\nEnter a number to see the description: ");
            
          choice = int.Parse(Console.ReadLine());
          
          switch (choice)
          {
                case 1:
                Console.WriteLine(" Yellowstone National Park is an American national park located in the western United States, largely in the northwest corner of Wyoming and extending into Montana and Idaho. ");
                break;
                case 2:
                Console.WriteLine(" Banff National Park is Canada's oldest national park, established in 1885 as Rocky Mountains Park. Located in Alberta's Rocky Mountains, 110–180 kilometres west of Calgary, Banff encompasses 6,641 square kilometres of mountainous terrain, with many glaciers and ice fields, dense coniferous forest, and alpine landscapes. ");
                break;
                case 3:
                Console.WriteLine(" Plitvice Lakes National Park is one of the oldest and largest national parks in Croatia. In 1972, Plitvice Lakes National Park was inscibed on the UNESCO World Heritage list, due to its outstanding and picturesque series of tufa lakes, caves, connected by waterfalls. ");
                return;
                default:
                Console.WriteLine("Invalid choice.");
                break;
            }
            break;
            case 3:
            Console.WriteLine("\nHere are the list of cities to travel: ");
            Console.WriteLine("1. New York City, USA");
            Console.WriteLine("2. Tokyo, Japan");
            Console.WriteLine("3. Dubai, UAE");
            
            Console.WriteLine("\nEnter a number to see the description: ");
            
            choice = int.Parse(Console.ReadLine());
            
            switch  (choice)
            {
                case 1:
                Console.WriteLine(" New York, often called New York City or NYC, is the most populous city in the United States. New York City is home to some of the world's most famous landmarks, including the Statue of Liberty, Empire State Building, Central Park, and Times Square. These landmarks attract millions of visitors every year. ");
                break;
                case 2:
                Console.WriteLine(" Tokyo, historically Tokio and officially the Tokyo Metropolis, is the capital and largest city of Japan. Tokyo offers a fascinating blend of traditional Japanese culture and modernity, making it a truly unique experience for visitors. ");
                break;
                case 3: 
                Console.WriteLine(" Dubai is known for its luxurious accommodations, shopping malls, and experiences, offering visitors the chance to experience some of the world's most lavish hotels, restaurants, and attractions. ");
                return;
                default:
                Console.WriteLine(" Invalid choice.");
                break;
            }
            break;
            case 4:
            Console.WriteLine("\nHere are the list of historical landmarks to travel: ");
            Console.WriteLine("1. Taj Mahal");
            Console.WriteLine("2. Eiffel Tower");
            Console.WriteLine("3. Collesseum");
            
            Console.WriteLine("\nEnter a number to see the description: ");
            
            choice = int.Parse(Console.ReadLine());
            
            switch (choice)
            {
                case 1:
                Console.WriteLine(" Taj Mahal is a white marble mausoleum located in Agra, India. It was commissioned by Mughal Emperor Shah Jahan in memory of his beloved wife Mumtaz Mahal, who passed away during childbirth in 1631. Taj Mahal is known for its stunning architectural beauty and intricate decorative details, such as its white marble façade adorned with intricate carvings and inlaid with precious stones.");
                break;
                case 2:
                Console.WriteLine(" Eiffel Tower is a wrought-iron lattice tower located on the Champ de Mars in Paris, France. It was designed by Gustave Eiffel and was built as the entrance arch for the 1889 World's Fair. The tower stands at 324 meters (1,063 feet) tall, making it one of the most recognizable landmarks in the world. ");
                break;
                case 3:
                Console.WriteLine(" Colosseum, also known as the Flavian Amphitheatre, is an ancient Roman landmark located in the center of Rome, Italy. It is considered one of the greatest architectural achievements of the ancient world, and is recognized as one of the most iconic symbols of Rome. ");
                return;
                default:
                Console.WriteLine(" Invalid choice.");
                break;
            }
            break;
            default:
            Console.WriteLine("Invalid selection. Please try again.");
            break;
        }
    }
}
