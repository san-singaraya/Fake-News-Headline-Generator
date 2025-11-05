[1412a800-ce16-4b77-9c49-ab6af22190c3.txt](https://github.com/user-attachments/files/23353484/1412a800-ce16-4b77-9c49-ab6af22190c3.txt)# Fake-News-Headline-Generator
Fake News Headline Generator Description


[Uploading 1412a80Repository: san-singaraya/fake-news-headline-generator
Files analyzed: 2

Estimated tokens: 498

Directory structure:
└── san-singaraya-fake-news-headline-generator/
    ├── README.md
    └── python project/
        └── Fake_News_Headline_Generator.py


================================================
FILE: README.md
================================================
# Fake-News-Headline-Generator
Fake News Headline Generator Description

https://gitdocs1.s3.amazonaws.com/digests/san-singaraya-fake-news-headline-generator/d9b3aaef-4e62-43bb-a9c7-ab90ad1fc247.txt<img width="772" height="1026" alt="Screenshot 2025-11-05 at 12 53 52 AM" src="https://github.com/user-attachments/assets/3cdf5c1e-f655-45e9-aac9-59aa43803566" />



================================================
FILE: python project/Fake_News_Headline_Generator.py
================================================
# 1 - import the random module
import random


# 2- create subjects
subjects = [
    "Shahrukh Khan",
    "Virat Kohli",
    "A Mumbai Cat",
    "A group of monkeys",
    "Prime Minister Modi",
    "Nirmal Sitharaman",
    "Auto Rickshaw Driver from Delhi"
]

actions = [
    "Launches",
    "cancels",
    "dances with",
    "eats",
    "declares war on",
    "orders",
    "celebrates"
]

places_or_things = [
    "at Red Fort",
    "in Mumbai Local Train",
    "a plate of samosa",
    "inside parliment",
    "at ganga ghat",
    "during IPL match",
    "at Indian Gate"
]

# 3- start the headline generation loop
while True :
    subject = random.choice(subjects)
    action = random.choice(actions)
    place_or_thing = random.choice(places_or_things)


    headline = f"BREAKING NEWS : {subject} {action} {place_or_thing}"
    print("\n" + headline)

    user_input = input("\nDo you want another headline? (yes/no)").strip().lower()
    if user_input == "no":
        break

#print goodbye message
print("\nThanks for using the Fake News Headline Generator. Have a fun day")



0-ce16-4b77-9c49-ab6af22190c3.txt…]()

<img width="772" height="1026" alt="Screenshot 2025-11-05 at 12 53 52 AM" src="https://github.com/user-attachments/assets/3cdf5c1e-f655-45e9-aac9-59aa43803566" />
