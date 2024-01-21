# Soul-Sync
Soul-Sync is a compassionate and supportive social-media platform designed specifically for individuals facing mental health challenges such as anxiety, stress, depression, and various other mental ailness. This comprehensive app offers a range of features designed to promote well-being, self-care, and community support. It is a platform that recognizes the importance of mental health and aims to provide a holistic approach to well-being. It combines mood tracking, task suggestions, therapeutic games, meditation, and a supportive community to help users navigate the challenges of mental health.

# Key features of this app
1. Mood Tracking:
Upon opening the app, users can input their current mood on a scale of 1 to 10. This feature serves as a personal reflection tool, allowing users to track their emotional well-being over time.

2. Mood-Based Content:
The app intelligently curates content based on the user's reported mood. Whether it's inspiring quotes, uplifting stories, or helpful resources, the content is tailored to support the user's emotional state.

3. Task Suggestions:
Soul-Sync suggests personalized tasks to improve the user's mood. These tasks range from simple activities to more involved exercises, providing users with actionable steps to enhance their mental well-being.

4. Therapeutic Games:
Engage in therapeutic games designed to provide a sense of accomplishment and joy. These games are carefully selected to contribute positively to the user's mental health.

5. Meditation and Journaling:
Incorporate mindfulness into your routine with meditation exercises. The app also includes a journaling feature, allowing users to express their thoughts and emotions in a private space.

6. Forest for Focus:
Boost concentration and reduce stress by utilizing the "Forest" feature, where users can grow a virtual forest by staying focused and resisting the urge to use their phones.

7. Anonymous Chat:
Connect with others anonymously for peer support. Share experiences, offer encouragement, and build a sense of community without the fear of judgment.

8. Community Support:
Join various support groups and communities within the app. Engage in open discussions, share insights, and connect with others who understand the challenges you're facing.

9. Curated Content:
Access a curated library of articles, videos, and resources aimed at breaking the cycle of mental illness. Discover valuable insights and strategies to navigate the journey towards mental wellness.

10. Streak Maintenance for Consistency:
Establish and maintain positive habits by leveraging the streak feature. Record your daily activities, such as mood tracking, meditation, or completing suggested tasks, to build and track your streaks. Consistency is key to fostering long-term well-being.


# Why this app?
With growing technologies and advancements, along with changes to the environment, it has been seen that this generation faces problems with a growing number of individuals dealing with their mental health. We believe that along with taking care of the physical health, a significant amount of care and attention has to be given to one's mental health too. And while people dealing with such problems, the norm and popularity of the social media platforms do no good, instead invoke a sense of fake world showcasing things which are far away from the reality of this world, hence increasing those problems more.

Hence, Soul-Sync - A social media platform is specially designed to help people deal with their growing difficulty revolving around mental health. On times when nothing seems right, Soul-Sync is there to get yourself together, motivating you to be better for yoourself, with features like to-do lists, and streaks. Not only that, it makes healing a fun thing by therapeutic games and music. Got nobody to talk? Don't worry it has a supportive community where you are always having people around you sharing a progressive journey with you, with an addition to anonimous chatting so you can vent out all your worries with no worrries.


# How the App works?

1. As users open the app, the frontend, developed using React Native, prompts them to input their current mood on a scale of 1 to 10. The data is then securely transmitted to the backend, built on Node.js and Express.js, which stores the information in Google Cloud Firestore, a scalable NoSQL database.

2. Utilizing Google Cloud Firestore, the backend dynamically fetches and serves personalized content based on the user's self-reported mood. The frontend, driven by React Native and Redux for state management, displays this content in a user-friendly format. 

3. Personalized task suggestions, managed by the backend, are presented to users based on their mood. Firebase Cloud Functions come into play, executing serverless functions to process and deliver these suggestions. Users can then choose to engage with these tasks directly through the frontend.

4. The app incorporates therapeutic games, seamlessly integrated using React Native. These games are designed to provide a positive and enjoyable experience for users. The frontend communicates with the backend to record user progress and achievements using Google Cloud Firestore.

5. The meditation feature, powered by React Native components, guides users through sessions. Journaling, implemented with Firebase Realtime Database, allows users to store and retrieve personal reflections securely. Both features enhance mindfulness and are easily accessible through the frontend.

6. The "Forest" feature is implemented using React Native components for the frontend and Google Cloud Firestore to store user progress. Users engage with the virtual forest by staying focused, with Firebase Cloud Functions managing rewards and updates to the user's forest status.

7. Firebase Authentication ensures secure user logins, while anonymous chat functionality is facilitated by Firebase Cloud Functions. The backend orchestrates the anonymous chat feature, providing a safe space for users to connect and share experiences without revealing their identities.

8. Various support groups and communities are hosted on the backend, with Google Cloud Firestore managing the data. React Native on the frontend allows users to seamlessly join, engage in discussions, and build connections within the supportive communities.

9.Curated content, stored in Google Cloud Firestore, is easily accessible through the frontend. The content, ranging from articles to videos, is carefully chosen to break the cycle of mental illness, providing valuable insights for users navigating their mental health journey.   

10. Curated content, stored in Google Cloud Firestore, is easily accessible through the frontend. The content, ranging from articles to videos, is carefully chosen to break the cycle of mental illness, providing valuable insights for users navigating their mental health journey.
