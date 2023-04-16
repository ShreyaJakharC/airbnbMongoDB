# AirBnB MongoDB Analysis



1. The query given below gives us the 2 listings from the listings collection. 
<br>
Query:

```bash
db.listings.find().limit(2)
```
Output:
<pre>
[
  {
    _id: ObjectId("643b555124ed49838615859c"),
    id: 39870,
    listing_url: 'https://www.airbnb.com/rooms/39870',
    scrape_id: Long("20230319180930"),
    last_scraped: '2023-03-19',
    source: 'city scrape',
    name: 'Close to Vanderbilt 2',
    description: 'Since I am older, I need for guests to be vaccinated.<br />This is a room and private bathroom in my cozy cottage near Vanderbilt and other area colleges. It is also close to the bus  or a short uber ride to downtown.   I do  have a petite boxer ,Grace. She stays in the kitchen downstairs .She is VERY friendly.<br />The bed is a double iron bed and may not be suitable for tall couples, since it has a foot board.<br /><br /><b>The space</b><br />Quiet house walking distance to Vanderbilt University. Comfortable room with private bathroom.<br /><br /><b>Other things to note</b><br />Since I am older and the room is in my home, I need for guests to be vaccinated.',
    neighborhood_overview: 'The house is in a safe, quiet,  "college" neighborhood.',
    picture_url: 'https://a0.muscache.com/pictures/miso/Hosting-39870/original/2e51ef52-cb3b-4c2b-9972-8ce50b6acff7.jpeg',
    host_id: 171184,
    host_url: 'https://www.airbnb.com/users/show/171184',
    host_name: 'Evelyn',
    host_since: '2010-07-18',
    host_location: 'Nashville, TN',
    host_about: 'I am a newly retired elementary school teacher. I like to run, walk, swim, read and meet new people. I  have three children. The girls are young adults and my son is a freshman away at college. I My cozy home is within walking distance to Vanderbilt and Belmont Universities, restaurants and shopping.',
    host_response_time: 'within an hour',
    host_response_rate: '100%',
    host_acceptance_rate: '92%',
    host_is_superhost: 't',
    host_thumbnail_url: 'https://a0.muscache.com/im/users/171184/profile_pic/1389073105/original.jpg?aki_policy=profile_small',
    host_picture_url: 'https://a0.muscache.com/im/users/171184/profile_pic/1389073105/original.jpg?aki_policy=profile_x_medium',
    host_neighbourhood: '',
    host_listings_count: 1,
    host_total_listings_count: 3,
    host_verifications: "['email', 'phone']",
    host_has_profile_pic: 't',
    host_identity_verified: 't',
    neighbourhood: 'Nashville, Tennessee, United States',
    neighbourhood_cleansed: 'District 18',
    neighbourhood_group_cleansed: '',
    latitude: 36.12523,
    longitude: -86.81278,
    property_type: 'Private room in home',
    room_type: 'Private room',
    accommodates: 2,
    bathrooms: '',
    bathrooms_text: '1 private bath',
    bedrooms: 1,
    beds: 1,
    amenities: '["Iron", "Keypad", "Luggage dropoff allowed", "Free parking on premises", "Wifi", "Washer", "Coffee maker", "Essentials", "Refrigerator", "Self check-in", "Extra pillows and blankets", "Hair dryer", "Shampoo", "Fire extinguisher", "Hot water", "Dryer", "Smoke alarm", "Air conditioning", "Carbon monoxide alarm", "Bed linens", "Microwave", "Hangers", "Heating"]',
    price: '$70.00',
    minimum_nights: 1,
    maximum_nights: 1125,
    minimum_minimum_nights: 1,
    maximum_minimum_nights: 1,
    minimum_maximum_nights: 1125,
    maximum_maximum_nights: 1125,
    minimum_nights_avg_ntm: 1,
    maximum_nights_avg_ntm: 1125,
    calendar_updated: '',
    has_availability: 't',
    availability_30: 5,
    availability_60: 17,
    availability_90: 30,
    availability_365: 174,
    calendar_last_scraped: '2023-03-19',
    number_of_reviews: 349,
    number_of_reviews_ltm: 68,
    number_of_reviews_l30d: 1,
    first_review: '2016-09-16',
    last_review: '2023-02-26',
    review_scores_rating: 4.94,
    review_scores_accuracy: 4.96,
    review_scores_cleanliness: 4.95,
    review_scores_checkin: 4.99,
    review_scores_communication: 4.97,
    review_scores_location: 4.95,
    review_scores_value: 4.94,
    license: '',
    instant_bookable: 'f',
    calculated_host_listings_count: 1,
    calculated_host_listings_count_entire_homes: 0,
    calculated_host_listings_count_private_rooms: 1,
    calculated_host_listings_count_shared_rooms: 0,
    reviews_per_month: 4.41
  },
  {
    _id: ObjectId("643b555124ed49838615859b"),
    id: 6422,
    listing_url: 'https://www.airbnb.com/rooms/6422',
    scrape_id: Long("20230319180930"),
    last_scraped: '2023-03-19',
    source: 'city scrape',
    name: 'Nashville Charm',
    description: "30 day plus rental - book for one month and then discuss longer rental option. Turn of century bungalow in East Nashville with city park, greenway and river behind house. Walk to shops, eateries and music venues. Downtown located 19 blocks away.  Rental unit is accessed through front door of home and located on second floor. The furnished space includes a combined sitting room with desk, kitchenette and wardrobe, a master bath with jacuzzi and shower, and a small bedroom with double bed.<br /><br /><b>The space</b><br />My husband and I have lived in our 1920's historic bungalow for almost 25 years. It backs up to city park with a 9 mile greenway along the river, is located 19 blocks from downtown (bus stop 3 doors away), within walking distance of hip East Nashville neighborhood eateries/clubs/shops and 1 block to golf course and tennis courts. Rental unit is accessed through front door of home and is located on second floor. The furnished space includes a combined sitting room with d",
    neighborhood_overview: "Historic East Nashville is home to many new and old favorite eateries (from barbeque and meat-n-three's to French and Italian cuisine and everything in between- including beloved Mas Taco's and Prince's Hot Chicken), art galleries, music venues, wine bar, micro beer outlets, etc. Our home is 15 minutes from the airport, 19 blocks from downtown Nashville, backs up to Shelby Park with a duck pond and 9 mile greenway along the river, a public golf course at the end of the street and tennis court across the park opening. Some guests spend their time at the lower Broadway honkey-tonks while others enjoy the local eateries and small music venues throughout our Little-Five Points neighborhood. Within 15 minutes of most major universities, hospitals, drug and grocery stores and other needed services. East Nashville really does have it all!",
    picture_url: 'https://a0.muscache.com/pictures/miso/Hosting-6422/original/c1ff6506-8d8b-4ccf-927a-0e2275270879.jpeg',
    host_id: 12172,
    host_url: 'https://www.airbnb.com/users/show/12172',
    host_name: 'Michele',
    host_since: '2009-04-03',
    host_location: 'Nashville, TN',
    host_about: "My husband and I are parents of 5 grown children, living in various places in the US attending school/working. We've lived in East Nashville for 20 years. My husband, Collier, is a recently retired public defender and I am self-employed, having previously worked with various non-profit organizations and continuing to mediate and write. Most of my non-profit work was with community-based economic development organizations, racial and social justice groups, mentally and physically challenged people and women-focused efforts. We especially like activists, artists, adventurers and visionaries, but anyone wanting to travel to Nashville and get a real feel for our small town/ city and its friendly inhabitants would be happy staying with us. We live a simple life and believe in radical hospitality because we are all visitors in this world.",
    host_response_time: 'within an hour',
    host_response_rate: '100%',
    host_acceptance_rate: '0%',
    host_is_superhost: 'f',
    host_thumbnail_url: 'https://a0.muscache.com/im/users/12172/profile_pic/1375806408/original.jpg?aki_policy=profile_small',
    host_picture_url: 'https://a0.muscache.com/im/users/12172/profile_pic/1375806408/original.jpg?aki_policy=profile_x_medium',
    host_neighbourhood: '',
    host_listings_count: 1,
    host_total_listings_count: 1,
    host_verifications: "['phone']",
    host_has_profile_pic: 't',
    host_identity_verified: 't',
    neighbourhood: 'Nashville, Tennessee, United States',
    neighbourhood_cleansed: 'District 6',
    neighbourhood_group_cleansed: '',
    latitude: 36.17315,
    longitude: -86.73581,
    property_type: 'Private room in home',
    room_type: 'Private room',
    accommodates: 1,
    bathrooms: '',
    bathrooms_text: '1 private bath',
    bedrooms: 1,
    beds: 1,
    amenities: '["Lock on bedroom door", "Iron", "Washer \\u2013\\u00a0In building", "Kayak", "Private living room", "Freezer", "Ethernet connection", "TV", "Mini fridge", "Luggage dropoff allowed", "Bathtub", "Wifi", "Ceiling fan", "Essentials", "First aid kit", "Cooking basics", "Extra pillows and blankets", "Hair dryer", "Shampoo", "Books and reading material", "Dedicated workspace", "Hammock", "Shared patio or balcony", "Toaster", "Dr. Bronners body soap", "Cleaning products", "All natural conditioner", "Fire extinguisher", "Hot water", "Backyard", "Free street parking", "Coffee maker: pour-over coffee", "Smoke alarm", "Air conditioning", "Outdoor dining area", "Carbon monoxide alarm", "Hot water kettle", "Bed linens", "Clothing storage: closet, wardrobe, and dresser", "Coffee", "Long term stays allowed", "Microwave", "Portable fans", "Kitchen", "Hangers", "Dishes and silverware", "Room-darkening shades", "Outdoor furniture", "Dryer \\u2013 In building", "Host greets you", "Heating", "Free driveway parking on premises \\u2013 1 space"]',
    price: '$43.00',
    minimum_nights: 30,
    maximum_nights: 365,
    minimum_minimum_nights: 30,
    maximum_minimum_nights: 30,
    minimum_maximum_nights: 365,
    maximum_maximum_nights: 365,
    minimum_nights_avg_ntm: 30,
    maximum_nights_avg_ntm: 365,
    calendar_updated: '',
    has_availability: 't',
    availability_30: 0,
    availability_60: 4,
    availability_90: 34,
    availability_365: 309,
    calendar_last_scraped: '2023-03-19',
    number_of_reviews: 674,
    number_of_reviews_ltm: 0,
    number_of_reviews_l30d: 0,
    first_review: '2009-04-30',
    last_review: '2020-03-03',
    review_scores_rating: 4.95,
    review_scores_accuracy: 4.94,
    review_scores_cleanliness: 4.96,
    review_scores_checkin: 4.97,
    review_scores_communication: 4.96,
    review_scores_location: 4.92,
    review_scores_value: 4.98,
    license: '',
    instant_bookable: 'f',
    calculated_host_listings_count: 1,
    calculated_host_listings_count_entire_homes: 0,
    calculated_host_listings_count_private_rooms: 1,
    calculated_host_listings_count_shared_rooms: 0,
    reviews_per_month: 3.99
  }
]
</pre>

2. 
<br>
Query:
```bash
db.listings.find().limit(10).pretty()
```
I did put the ouput for 3 documents because each documnet had a lot of information. Getting 10 increase the output greatly.
```bash
db.listings.find().limit(3).pretty()
```
Output:
<pre>
[
  {
    _id: ObjectId("643b555124ed49838615859c"),
    id: 39870,
    listing_url: 'https://www.airbnb.com/rooms/39870',
    scrape_id: Long("20230319180930"),
    last_scraped: '2023-03-19',
    source: 'city scrape',
    name: 'Close to Vanderbilt 2',
    description: 'Since I am older, I need for guests to be vaccinated.<br />This is a room and private bathroom in my cozy cottage near Vanderbilt and other area colleges. It is also close to the bus  or a short uber ride to downtown.   I do  have a petite boxer ,Grace. She stays in the kitchen downstairs .She is VERY friendly.<br />The bed is a double iron bed and may not be suitable for tall couples, since it has a foot board.<br /><br /><b>The space</b><br />Quiet house walking distance to Vanderbilt University. Comfortable room with private bathroom.<br /><br /><b>Other things to note</b><br />Since I am older and the room is in my home, I need for guests to be vaccinated.',
    neighborhood_overview: 'The house is in a safe, quiet,  "college" neighborhood.',
    picture_url: 'https://a0.muscache.com/pictures/miso/Hosting-39870/original/2e51ef52-cb3b-4c2b-9972-8ce50b6acff7.jpeg',
    host_id: 171184,
    host_url: 'https://www.airbnb.com/users/show/171184',
    host_name: 'Evelyn',
    host_since: '2010-07-18',
    host_location: 'Nashville, TN',
    host_about: 'I am a newly retired elementary school teacher. I like to run, walk, swim, read and meet new people. I  have three children. The girls are young adults and my son is a freshman away at college. I My cozy home is within walking distance to Vanderbilt and Belmont Universities, restaurants and shopping.',
    host_response_time: 'within an hour',
    host_response_rate: '100%',
    host_acceptance_rate: '92%',
    host_is_superhost: 't',
    host_thumbnail_url: 'https://a0.muscache.com/im/users/171184/profile_pic/1389073105/original.jpg?aki_policy=profile_small',
    host_picture_url: 'https://a0.muscache.com/im/users/171184/profile_pic/1389073105/original.jpg?aki_policy=profile_x_medium',
    host_neighbourhood: '',
    host_listings_count: 1,
    host_total_listings_count: 3,
    host_verifications: "['email', 'phone']",
    host_has_profile_pic: 't',
    host_identity_verified: 't',
    neighbourhood: 'Nashville, Tennessee, United States',
    neighbourhood_cleansed: 'District 18',
    neighbourhood_group_cleansed: '',
    latitude: 36.12523,
    longitude: -86.81278,
    property_type: 'Private room in home',
    room_type: 'Private room',
    accommodates: 2,
    bathrooms: '',
    bathrooms_text: '1 private bath',
    bedrooms: 1,
    beds: 1,
    amenities: '["Iron", "Keypad", "Luggage dropoff allowed", "Free parking on premises", "Wifi", "Washer", "Coffee maker", "Essentials", "Refrigerator", "Self check-in", "Extra pillows and blankets", "Hair dryer", "Shampoo", "Fire extinguisher", "Hot water", "Dryer", "Smoke alarm", "Air conditioning", "Carbon monoxide alarm", "Bed linens", "Microwave", "Hangers", "Heating"]',
    price: '$70.00',
    minimum_nights: 1,
    maximum_nights: 1125,
    minimum_minimum_nights: 1,
    maximum_minimum_nights: 1,
    minimum_maximum_nights: 1125,
    maximum_maximum_nights: 1125,
    minimum_nights_avg_ntm: 1,
    maximum_nights_avg_ntm: 1125,
    calendar_updated: '',
    has_availability: 't',
    availability_30: 5,
    availability_60: 17,
    availability_90: 30,
    availability_365: 174,
    calendar_last_scraped: '2023-03-19',
    number_of_reviews: 349,
    number_of_reviews_ltm: 68,
    number_of_reviews_l30d: 1,
    first_review: '2016-09-16',
    last_review: '2023-02-26',
    review_scores_rating: 4.94,
    review_scores_accuracy: 4.96,
    review_scores_cleanliness: 4.95,
    review_scores_checkin: 4.99,
    review_scores_communication: 4.97,
    review_scores_location: 4.95,
    review_scores_value: 4.94,
    license: '',
    instant_bookable: 'f',
    calculated_host_listings_count: 1,
    calculated_host_listings_count_entire_homes: 0,
    calculated_host_listings_count_private_rooms: 1,
    calculated_host_listings_count_shared_rooms: 0,
    reviews_per_month: 4.41
  },
  {
    _id: ObjectId("643b555124ed49838615859b"),
    id: 6422,
    listing_url: 'https://www.airbnb.com/rooms/6422',
    scrape_id: Long("20230319180930"),
    last_scraped: '2023-03-19',
    source: 'city scrape',
    name: 'Nashville Charm',
    description: "30 day plus rental - book for one month and then discuss longer rental option. Turn of century bungalow in East Nashville with city park, greenway and river behind house. Walk to shops, eateries and music venues. Downtown located 19 blocks away.  Rental unit is accessed through front door of home and located on second floor. The furnished space includes a combined sitting room with desk, kitchenette and wardrobe, a master bath with jacuzzi and shower, and a small bedroom with double bed.<br /><br /><b>The space</b><br />My husband and I have lived in our 1920's historic bungalow for almost 25 years. It backs up to city park with a 9 mile greenway along the river, is located 19 blocks from downtown (bus stop 3 doors away), within walking distance of hip East Nashville neighborhood eateries/clubs/shops and 1 block to golf course and tennis courts. Rental unit is accessed through front door of home and is located on second floor. The furnished space includes a combined sitting room with d",
    neighborhood_overview: "Historic East Nashville is home to many new and old favorite eateries (from barbeque and meat-n-three's to French and Italian cuisine and everything in between- including beloved Mas Taco's and Prince's Hot Chicken), art galleries, music venues, wine bar, micro beer outlets, etc. Our home is 15 minutes from the airport, 19 blocks from downtown Nashville, backs up to Shelby Park with a duck pond and 9 mile greenway along the river, a public golf course at the end of the street and tennis court across the park opening. Some guests spend their time at the lower Broadway honkey-tonks while others enjoy the local eateries and small music venues throughout our Little-Five Points neighborhood. Within 15 minutes of most major universities, hospitals, drug and grocery stores and other needed services. East Nashville really does have it all!",
    picture_url: 'https://a0.muscache.com/pictures/miso/Hosting-6422/original/c1ff6506-8d8b-4ccf-927a-0e2275270879.jpeg',
    host_id: 12172,
    host_url: 'https://www.airbnb.com/users/show/12172',
    host_name: 'Michele',
    host_since: '2009-04-03',
    host_location: 'Nashville, TN',
    host_about: "My husband and I are parents of 5 grown children, living in various places in the US attending school/working. We've lived in East Nashville for 20 years. My husband, Collier, is a recently retired public defender and I am self-employed, having previously worked with various non-profit organizations and continuing to mediate and write. Most of my non-profit work was with community-based economic development organizations, racial and social justice groups, mentally and physically challenged people and women-focused efforts. We especially like activists, artists, adventurers and visionaries, but anyone wanting to travel to Nashville and get a real feel for our small town/ city and its friendly inhabitants would be happy staying with us. We live a simple life and believe in radical hospitality because we are all visitors in this world.",
    host_response_time: 'within an hour',
    host_response_rate: '100%',
    host_acceptance_rate: '0%',
    host_is_superhost: 'f',
    host_thumbnail_url: 'https://a0.muscache.com/im/users/12172/profile_pic/1375806408/original.jpg?aki_policy=profile_small',
    host_picture_url: 'https://a0.muscache.com/im/users/12172/profile_pic/1375806408/original.jpg?aki_policy=profile_x_medium',
    host_neighbourhood: '',
    host_listings_count: 1,
    host_total_listings_count: 1,
    host_verifications: "['phone']",
    host_has_profile_pic: 't',
    host_identity_verified: 't',
    neighbourhood: 'Nashville, Tennessee, United States',
    neighbourhood_cleansed: 'District 6',
    neighbourhood_group_cleansed: '',
    latitude: 36.17315,
    longitude: -86.73581,
    property_type: 'Private room in home',
    room_type: 'Private room',
    accommodates: 1,
    bathrooms: '',
    bathrooms_text: '1 private bath',
    bedrooms: 1,
    beds: 1,
    amenities: '["Lock on bedroom door", "Iron", "Washer \\u2013\\u00a0In building", "Kayak", "Private living room", "Freezer", "Ethernet connection", "TV", "Mini fridge", "Luggage dropoff allowed", "Bathtub", "Wifi", "Ceiling fan", "Essentials", "First aid kit", "Cooking basics", "Extra pillows and blankets", "Hair dryer", "Shampoo", "Books and reading material", "Dedicated workspace", "Hammock", "Shared patio or balcony", "Toaster", "Dr. Bronners body soap", "Cleaning products", "All natural conditioner", "Fire extinguisher", "Hot water", "Backyard", "Free street parking", "Coffee maker: pour-over coffee", "Smoke alarm", "Air conditioning", "Outdoor dining area", "Carbon monoxide alarm", "Hot water kettle", "Bed linens", "Clothing storage: closet, wardrobe, and dresser", "Coffee", "Long term stays allowed", "Microwave", "Portable fans", "Kitchen", "Hangers", "Dishes and silverware", "Room-darkening shades", "Outdoor furniture", "Dryer \\u2013 In building", "Host greets you", "Heating", "Free driveway parking on premises \\u2013 1 space"]',
    price: '$43.00',
    minimum_nights: 30,
    maximum_nights: 365,
    minimum_minimum_nights: 30,
    maximum_minimum_nights: 30,
    minimum_maximum_nights: 365,
    maximum_maximum_nights: 365,
    minimum_nights_avg_ntm: 30,
    maximum_nights_avg_ntm: 365,
    calendar_updated: '',
    has_availability: 't',
    availability_30: 0,
    availability_60: 4,
    availability_90: 34,
    availability_365: 309,
    calendar_last_scraped: '2023-03-19',
    number_of_reviews: 674,
    number_of_reviews_ltm: 0,
    number_of_reviews_l30d: 0,
    first_review: '2009-04-30',
    last_review: '2020-03-03',
    review_scores_rating: 4.95,
    review_scores_accuracy: 4.94,
    review_scores_cleanliness: 4.96,
    review_scores_checkin: 4.97,
    review_scores_communication: 4.96,
    review_scores_location: 4.92,
    review_scores_value: 4.98,
    license: '',
    instant_bookable: 'f',
    calculated_host_listings_count: 1,
    calculated_host_listings_count_entire_homes: 0,
    calculated_host_listings_count_private_rooms: 1,
    calculated_host_listings_count_shared_rooms: 0,
    reviews_per_month: 3.99
  },{
    _id: ObjectId("643b555124ed49838615859d"),
    id: 3648549,
    listing_url: 'https://www.airbnb.com/rooms/3648549',
    scrape_id: Long("20230319180930"),
    last_scraped: '2023-03-20',
    source: 'city scrape',
    name: 'Serene, Cozy Getaway; Lipscomb, Vanderbilt,12South',
    description: `*Our Airbnb is professionally cleaned & disinfected between each guest’s stay.*<br /><br />As we say in the South "Y'all come on in, make yourself at home!"<br />Create great memories in Music City & stay at Margie's Hideaway-850 sq. ft. Studio-with private entrance on lower floor.  It is a walk in basement and you will probabky hear us at times. You have completed privacy.<br />*NOTE-Not suitable for children under 12 years old<br /><br /><b>The space</b><br />ENTIRE BOTTOM FLOOR<br />     * Welcoming living room space <br />     * Queen bed with fresh, white linens<br />     * Two twin beds in great room<br />     * Central air conditioner/heat(Thermastat on main floor)<br />     * Kitchenette (microwave only)<br />     * Keurig coffeemaker<br />     * Variety of coffee/tea K-cups<br />     * Private, clean bathroom<br />     * Shower<br />     * Hairdryer<br />     * White, freshly laundered towels<br />     * Self check-in/out<br />     ** Step free access-no pulling luggage up ste`,
    neighborhood_overview: "Green Hills is a PRIME location and much sought after area of town! <br /> It is about 5-20 minutes from here to anywhere you want to go while you are in Nashville.  * A 5 -7 minute walk away is public transportation. <br /><br />GROCERY STORES,RESTAURANTS, AND MALL:<br />**Only 1.4 miles away are TRADER JOE's<br />** WHOLE FOODS and Whole Foods Health in the Hill Center<br />** Kroger<br />** GREEN HIILLS MALL (Nordstroms, Tiffanys, Aveda, The Loft, Apple Store, etc.)<br />** JET'S Pizza (delivers), GREEN HILLS GRILLE (delivers), Kohana, Which Wich, Wendy's (for the Frosty lovers!), Cheesecake Factory Restaurant, Caraba's, Panera Bread, Zoe's, California Pizza, Chipotle, JUST to name a few.<br />**Bank of America, Regions Bank, First Tennessee Bank, U.S. Bank and more.<br /><br />EXERCISE:<br />**Attention! RUNNERS and WALKERS: There is an outdoor track right beside our house on Lipscomb's High School athletic field that is available for your free use. <br /><br />LOCATION, LOCATION, ",
    picture_url: 'https://a0.muscache.com/pictures/482b8166-d993-48de-88ab-0f44918b7108.jpg',
    host_id: 931636,
    host_url: 'https://www.airbnb.com/users/show/931636',
    host_name: 'Debby',
    host_since: '2011-08-06',
    host_location: 'Nashville, TN',
    host_about: "I am an out-going human being who believes that what I give out to the world comes back to me. I am loving, honest, friendly, funny. I am an Office Administrator for a pediatric dentist, a former country music performer with my mother, 'Marge and Debby Rhoads, The Country Rhoads' and and AIRBNB host! Traveling is one of my passions.  I enjoy meeting new people. My hobbies: sewing, reading, singing, traveling, great movies, people watching, nature, helping people, reading self-help books, live music, plays, etc., etc., etc. One of my many goals is to climb Mt. Kilimanjaro in Africa. Anyone want to go with me? \n" +
      "I believe you will enjoy Margie's Hideaway. I named my Airbnb after my beautiful, talented, one-of-a-kind mother! Our Airbnb is about a 7 minute stroll to Lipscomb University/Academy campus. I went to school there 7th grade through college. So did my brother. My father was a Speech Professor there for many years. Our house is so close to Lipscomb I walked to school, ballgames, functions through sun, wind, rain, snow, sleet, and whatever came our way and BOY what great memories!",
    host_response_time: 'within an hour',
    host_response_rate: '100%',
    host_acceptance_rate: '100%',
    host_is_superhost: 't',
    host_thumbnail_url: 'https://a0.muscache.com/im/pictures/user/1bf9abec-c6db-44f9-a8f4-edaeab17655f.jpg?aki_policy=profile_small',
    host_picture_url: 'https://a0.muscache.com/im/pictures/user/1bf9abec-c6db-44f9-a8f4-edaeab17655f.jpg?aki_policy=profile_x_medium',
    host_neighbourhood: '',
    host_listings_count: 1,
    host_total_listings_count: 1,
    host_verifications: "['email', 'phone']",
    host_has_profile_pic: 't',
    host_identity_verified: 't',
    neighbourhood: 'Nashville, Tennessee, United States',
    neighbourhood_cleansed: 'District 25',
    neighbourhood_group_cleansed: '',
    latitude: 36.10373,
    longitude: -86.79625,
    property_type: 'Entire rental unit',
    room_type: 'Entire home/apt',
    accommodates: 4,
    bathrooms: '',
    bathrooms_text: '1 bath',
    bedrooms: 1,
    beds: 3,
    amenities: '["Wine glasses", "Iron", "Body soap", "Private entrance", "Keypad", "Luggage dropoff allowed", "Free parking on premises", "Wifi", "Washer", "Coffee maker", "Ceiling fan", "Essentials", "First aid kit", "Refrigerator", "Self check-in", "Extra pillows and blankets", "Clothing storage: closet and dresser", "TV with standard cable", "Single level home", "Hair dryer", "Shampoo", "Books and reading material", "Backyard", "Toaster", "Fire extinguisher", "Hot water", "Dryer", "Safe", "Smoke alarm", "Air conditioning", "Carbon monoxide alarm", "Bed linens", "Patio or balcony", "Long term stays allowed", "Microwave", "Dishes and silverware", "Hangers", "Dining table", "Heating"]',
    price: '$143.00',
    minimum_nights: 2,
    maximum_nights: 34,
    minimum_minimum_nights: 1,
    maximum_minimum_nights: 2,
    minimum_maximum_nights: 1125,
    maximum_maximum_nights: 1125,
    minimum_nights_avg_ntm: 1.7,
    maximum_nights_avg_ntm: 1125,
    calendar_updated: '',
    has_availability: 't',
    availability_30: 0,
    availability_60: 0,
    availability_90: 0,
    availability_365: 0,
    calendar_last_scraped: '2023-03-20',
    number_of_reviews: 141,
    number_of_reviews_ltm: 25,
    number_of_reviews_l30d: 0,
    first_review: '2016-10-23',
    last_review: '2022-11-14',
    review_scores_rating: 4.93,
    review_scores_accuracy: 4.95,
    review_scores_cleanliness: 4.91,
    review_scores_checkin: 4.97,
    review_scores_communication: 4.97,
    review_scores_location: 4.94,
    review_scores_value: 4.93,
    license: '',
    instant_bookable: 'f',
    calculated_host_listings_count: 1,
    calculated_host_listings_count_entire_homes: 1,
    calculated_host_listings_count_private_rooms: 0,
    calculated_host_listings_count_shared_rooms: 0,
    reviews_per_month: 1.81
  }
]
- Here I used the limit 3 because the document had a lot of columns that made the output very large.
</pre>


3. 
Query:
```bash
```
</pre>
Output:
<pre>
</pre>
db.listings.find(
  { $and: [
    {host_id: { $in: [39870, 3648549] }}]
  },
  { 
    name: 1,
    price: 1,
    neighbourhood: 1,
    host_name: 1,
    host_is_superhost: 1,
    _id: 0
  }
)


```bash
db.listings.find(
  { 
    "host_id":  {430052, 3648549}
  },
  { 
    "name": 1,
    "price": 1,
    "neighbourhood": 1,
    "host_name": 1,
    "host_is_superhost": 1,
    "_id": 0
  }
)

db.listings.find(
  { 
    "host_id": { "$in": [430052, 3648549] }
  },
  { 
    "name": 1,
    "price": 1,
    "neighbourhood": 1,
    "host_name": 1,
    "host_is_superhost": 1,
    "_id": 0
  }
)
```

4. This query helps us get the total number of host, which will be impossible to gwt if we try doing it individually.
Query:
```bash
db.listings.distinct("host_name")
```
Output:
<pre>
[
  NaN,                    '12th',                '12th South',
  'A.',                   'Aaron',               'Abbie And Corbin',
  'Abby',                 'Abdullatif',          'Abey',
  'Abigail',              'Abigail And Kyle',    'Abode (Nashville)',
  'Above Vacation',       'Abraham',             "Ad'Breona",
  'Adam',                 'Adam And Tia',        'Addison',
  'Adi',                  'Aditi',               'Adrian',
  'Adrienne',             'Agnes',               'Ahmet',
  'Aidan',                'Aide',                'Aieshia',
  'Aimee & Chris',        'Aj',                  'Ajay',
  'Akilah',               'Alaina',              'Alan',
  'Alana',                'Alayna',              'Albert',
  'Alberto',              'Albis Junior',        'Albron',
  'Alec',                 'Alece',               'Alectra',
  'Alena',                'Alex',                'Alex & Wes',
  'Alex From Abode',      'Alexa',               'Alexa & Emily',
  'Alexander',            'Alexanderia',         'Alexandra',
  'Alexandria',           'Alexis',              'Alexis N',
  'Ali',                  'Alianna & Kenneth',   'Alicia',
  'Alisa',                'Alison',              'Alissa',
  'All Around Knowledge', 'All En Stays',        'Allan',
  'Allen',                'Allen And  Jennifer', 'Alli',
  'Allie',                'Allin',               'Allison',
  'Allyson',              'Alphonse',            'Alphonso',
  'Alta',                 'Alvin',               'Aly',
  'Alynn',                'Alysha',              'Alyssa',
  'Alyssa & Konrad',      'Amanda',              'Amani',
  'Amarilis',             'Amber',               'Amber & Brett',
  'Amber & Jordan',       'Ambra',               'Amelia',
  'Amesia',               'Amory',               'Amy',
  'Amy & Brandon',        'Amy & Jarrod',        'Anastasia',
  'Anchor Rentals',       'Andi',                'Andi Jane',
  'Andrea',               'Andrew',              'Andrew & Lisa',
  'Andrew & Rachel',
  ... 1505 more items
]
</pre>


5. 
Query:
```bash
db.listings.find(
  {
    "$and": [
    { "neighbourhood": "Nashville, Tennessee, United States" },
    {"beds": { "$gt": 2 }}]
  },
  {
    "name": 1,
    "beds": 1,
    "review_scores_rating": 1,
    "price": 1,
    "_id": 0
  }
).sort({ "review_scores_rating": -1 })
```
</pre>
Output:
<pre>
[
  {
    name: 'CONDO IN THE HEART OF GREEN HILLS',
    beds: 4,
    price: '$700.00',
    review_scores_rating: ''
  },
  {
    name: 'Tyler House at East Nashville',
    beds: 4,
    price: '$357.00',
    review_scores_rating: ''
  },
  {
    name: 'East Nash Boho Bungalow',
    beds: 7,
    price: '$189.00',
    review_scores_rating: ''
  }
]
</pre>

6. 
Query:
```bash
db.listings.aggregate([
  { $group: { _id: "$host_id", count: { $sum: 1 } } },
  { $sort: { count: -1 } }
])
```
Output:
<pre>
[
  { _id: 101426897, count: 185 },
  { _id: 20772148, count: 173 },
  { _id: 134126657, count: 151 }
]
</pre>

7.  
```bash
    db.listings.aggregate([
  { $match: { review_scores_rating: { $gt: 95%5 } } },
  { $group: { _id: "$neighbourhood", average_rating: { $avg: "$review_scores_rating" } } },
  { $sort: { average_rating: -1 } }
])
- I am sorting here according to the average rating and because in my data set the rating were given out of 5, I am printing data that has rating avove 95% of 5.
```

Output:
<pre>
[
  { _id: 'Ashland City, Tennessee, United States', average_rating: 5 },
  { _id: 'NASHVILLE, Tennessee, United States', average_rating: 5 },
  {
    _id: 'Nashville Hermitage, Tennessee, United States',
    average_rating: 5
  }
]
</pre>