<h1 align="center">Blood Plasma Bot</h1>
<h4 align="center">A blood donation app for saving lives</h4>

<br>

<p>Blood Plasma Bot is a open source blood Donation app available for Android smartphones. Blood Plasma Bot searches, notifies and connect thousands of blood donors in three simple steps. Blood Plasma Bot app ensures hassle free blood donation and privacy of a blood donor. A blood donor can select any specific date and location to donate blood and find a suitable person who needs blood. Connecting blood donors and needy reduces time which increases the possibility of saving lives and also eliminates the shortage of blood.</p>

## Todo
* Add logic for the app
* Create a web api
* Add social media auth

## Tools used:
* Android studio (IDE)
* Java (logic)
* XML (design)
* Paint.Net (Image editting)
<br>
Abstract<br>
The aim of our project is to save lives of people by providing blood to them whenever
required. Our project i.e Blood Plasma Bot Application using Android studio is
developed so that users can view the information of nearby hospitals, blood banks and
they can also receive blood from various donors, to monitor the blood groups database
and to send the required blood during the need to our application users in case of
emergencies. We are focusing on building a network of people who can help each other
during an emergency. We have provided security for authenticated users as new users
have to register according to their requirements and perspectives andexisting users have
to login. This application regularly updates the information about the donors and the
administrator has complete access to the information about blood donation system. The
application that we are developing requires an active internet connection, it helps to
select the nearby hospital and donors instantly by tracing the user’s location using GPS,
it provides the list of blood banks in the users area. We provide an alert system for
accidents that occur off the cuff by using this feature, an ambulance will be sent to the
users location and also a message will be sent to the users family and friends, whichwill
let them know that the user has met with an accidentwithout any wastage of time. Thus
this application provides the required information quicker and also helps in giving the
right treatment at the right time.

<br><br>
CHAPTER 1<br>
INTRODUCTION<br>
1.1 Introduction<br>
Mobile technology has been helping us to tackle almost every problem that humans face
today. Evidently, since the start of mobile applications their usage has been tremendous.
So much so that more than 80% of human activities on smart phones has been on
applications. Mobile applications have been an integral part of our life in several ways
starting from helping us to connect to people, making money transactions to keeping us
healthy by exercising. The expanding use of the android-based smart phones makes the
reach of a problem-solving application easy even to people who cannot afford huge
medical bills. Due to such boundless usage, mobile application technology definitely
provides us with a platform to solve a major problem faced by everyone in the world
and that is the need of blood. It may be required by a person suffering from anomia, or
an accident it may also be required by a pregnant mother in case of emergency. In such
situations, it is not always feasible to reach out to blood plasma bots, as they need to
maintain a stable supply, in some over populated countries like “Bangladesh” the patient
has to register in a waiting list for specific blood type even in cases of emergency.so we
choose to develop a Blood Plasma Bot application. The main goal of this application is
the users in such a way that users can find different volunteer blood donors in their
locality through address and then request for the blood in case of emergency. The users
will be able to view information about different blood donors, the information of the
registers users who need blood in case of emergency and the blood donors who wish to
donate blood when required. All the personal information about blood donors will be
kept at the real time database.<br>
We can improve the efficiency of the Blood Plasma Bot system, thus overcome the
drawbacks of the existing system.<br>
The system will do the following activities:<br>
i. New User registration
<br>
ii. Update user profile<br>
iii. Remove user from the system<br>
iv. Record Realtime user details<br><br>
1.2 Objectives<br>
The objectives of the project are follows:<br>
i. To make an application that reduce the time to manage blood.<br>
ii. To keep real-time record of donor.<br>
iii. To communicate with donor from donor details.<br>
iv. To easy to search donor list in one click.<br><br>
1.3 Key Benefits<br>
This system has many features. Some of them are below:<br>
i. User Friendly Interface<br>
The user interface is just awesome. Anybody can operate the application with
some basic knowledge of Android mobile<br>
ii. Admin Privileges
In this system, admin can view, update, remove any profiles etc.<br>
iii. Security<br>
Login system is implemented. So, only admin can control the operations and
user can only registration and view. All activities are recorded in firebase realtime database and available to all users.<br>
iv. Time Savings<br>
In manual Blood manage system, the patient has to register in a waiting list for
specific blood type even in cases of emergency. But in our application user easy
to search donor list in one click.
<br><br>
CHAPTER 2<br>
BACKGROUND KNOWLEDGE<br>
2.1 Introduction<br>
The number of voluntary donors has been increased compared to blood donors that are
being paid. about Though there is an increase in voluntary blood donor, because of lack
of information blood donation, many people are not being able to donate blood. Because
of this reason, there have been continuous losses of acquirable blood from individuals
who are willing to donate blood. Emergency patients, who are in need of blood, usually
request blood through advertising on televisions or social media, with the series of
advert placement of donation of blood the patient may still not get the required amount
of blood needed at that particular time which is slow for information retrieval and
processing and also prone to errors in an emergency situation. But in Blood Finder
application easy to search of available blood donors in nearby areas in cases on
emergencies without any delay.<br><br>
2.2 Literature Review<br>
The system we present here is adequate for searching blood donors for available blood
and thereby saving valuable time and money. This application provides necessary
options to serve people on their emergency need making them free from worrying for
blood by providing lot of donors at a single click. Blood Finder Android Application is
a mobile-based application. This application is to create an e-Information about the
Receiver and organization that are related to donating the blood. This application help
to register all the donors, Blood collection details, blood issued details etc. When
registration is completed, then the user no need to login it will open automatically on
home page. They can modify their account information by updating username, mobile
number, blood group and contact details. A user is able to search blood request from the
search page. This application provides donors details and contact number. It will make
easier to find and contact with donors when needed
<br><br>
2.3 Problem Statement<br>
In manual Blood Plasma Bot system usually patient parents request blood through
advertising on televisions or social media, with the series of advert placement of
donation of blood the patient may still not get the required amount of blood needed at
that particular time which is slow for information retrieval and processing and also prone
to errors in an emergency situation. But using android mobile application Blood, easy
to search of available blood donors in nearby areas in cases on emergencies without any
delay.<br><br>
CHAPTER 3<br>
PROPOSED SYSTEM ANALYSIS AND DESIGN<br>
3.1 Introduction<br>
The Blood Plasma Bot application is android mobile based project. By using of this
application people who want to donate their blood can register in this application by
their details and person who needs blood can search and find the blood which group
they need. After searching a list of donors will be displayed then the user can
communicate with donor easily.<br><br>
3.2 System Analysis<br>
System analysis is the process of gathering and interpreting facts, diagnosing problems
and using the information to recommend improvements on the system. System analysis
is a problem-solving activity that requires intensive communication between the system
users and system developers.<br>
System analysis or study is an important phase of any system development process. The
system is viewed as a whole, the inputs are identified and the system is subjected to
close study to identify the problem areas. The solutions are given as a proposal. The
proposal is reviewed on user request and suitable changes are made. This loop ends as
soon as the user is satisfied with the proposal.<br>
The existing system is not totally automated. Though the system is computerized to a
particular extent, it has not to do a lot of manual work. <br>The different processes involved
are:<br>
i. Registration by Mobile Number instead of Email.<br>
ii. Authentication for Mobile Number.<br>
iii. User friendly.<br>
iv. High security.<br>
v. Easy to registration.<br>
vi. Easy to search donor.<br>
vii. Data can updated be easily because we use firebase real-time database.<br><br>
3.3 System Design<br>
The system can be installed in any Android phone and required a machine with Pentium
IV processor, 512 MB ram, 1GB sstorage to implement the system. The system is
implemented in JDK11.0.1, Android 4.4(Kit Kat), java, Kotlin, and Android Studio.<br><br>
3.4 Use case diagram<br>
SEEKER: In case of emergency, they can request for blood in which it gives
information about the donors present in that city. After getting the information they can
contact the donor.<br><br>
DONOR: The donors will register their details in the application and whenever the
blood is required, they will be contacted by the acceptor within his/her specified city.

<br><br>
CHAPTER 5<br>
TOOLS AND TECHNOLOGY USED<br>
5.1 Development Tools<br>
Many tools are used to develop the Application. Some of them are used for development
purpose and some of them are part of this application. Without them Blood Plasma Bot
Application cannot work properly.<br><br>
5.2 Android Studio<br>
Android Studio is the official integrated development environment (IDE) for Google's
Android operating system, built on JetBrains' IntelliJ IDEA software and designed
specifically for Android development. It is available for download on Windows, macOS
and Linux based operating systems. It is a replacement for the Eclipse Android
Development Tools (ADT) as the primary IDE for native Android application
development.<br>
The following features are provided in the current stable version:<br>
• Gradle-based build support<br>
• Android-specific refactoring and quick fixes<br>
• Lint tools to catch performance, usability, version compatibility and other
problems<br>
• ProGear integration and app-signing capabilities<br>
• Template-based wizards to create common Android designs and components<br>
• A rich layout editor that allows users to drag-and-drop UI components, option to
preview layouts on multiple screen configurations<br>
• Support for building Android Wear apps<br>
• Built-in support for Google Cloud Platform, enabling integration with Firebase
Cloud Messaging (Earlier 'Google Cloud Messaging') and Google App Engine<br>
• Android Virtual Device (Emulator) to run and debug apps in the Android studio.<br>
<br>
Android Studio supports all the same programming languages of IntelliJ (and CLion)
e.g., Java, C++, and Kotlin etc. But we use java in Blood Finder application. Because
java is a general-purpose programming language that is class-based, object-oriented,
and designed to have as few implementation dependencies as possible.<br><br>
5.3 Firebase Realtime Database<br>
The Firebase Realtime Database lets you build rich, collaborative applications by
allowing secure access to the database directly from client-side code. Data is persisted
locally, and even while offline, Realtime events continue to fire, giving the end user a
responsive experience. When the device regains connection, the real-time Database
synchronizes the local data changes with the remote updates that occurred while the
client was offline, merging any conflicts automatically.<br>
The Realtime Database provides a flexible, expression-based rules language, called
Firebase Realtime Database Security Rules, to define how your data should be
structured and when data can be read from or written to. When integrated with Firebase
Authentication, developers can define who has access to what data, and how they can
access it.<br>
The Realtime Database is a NoSQL database and as such has different optimizations
and functionality compared to a relational database. The Realtime Database API is
designed to only allow operations that can be executed quickly. This enables you to
build a great real-time experience that can serve millions of users without compromising
on responsiveness. Because of this, it is important to think about how users need to
access your data and then structure it accordingly.<br><br>
5.3.1 Key capabilities<br>
I. Real-time: Instead of typical HTTP requests, the Firebase Realtime Database
uses data synchronization every time data changes, any connected device receives
that update within milliseconds. Provide collaborative and immersive experiences
without thinking about networking code.<br>

II. Offline: Firebase apps remain responsive even when offline because the Firebase
Realtime Database SDK persists your data to disk. Once connectivity is reestablished, the client device receives any changes it missed, synchronizing it
with the current server state.<br>
III. Accessible from Client Devices: The Firebase Realtime Database can be
accessed directly from a mobile device or web browser; there’s no need for an
application server. Security and data validation are available through the Firebase
Realtime Database Security Rules, expression-based rules that are executed when
data is read or written.<br>
IV. Scale across multiple databases: With Firebase Realtime Database on the Blaze
pricing plan, you can support your app's data needs at scale by splitting your data
across multiple database instances in the same Firebase project. Streamline
authentication with Firebase Authentication on your project and authenticate
users across your database instances. Control access to the data in each database
with custom Firebase Realtime Database Rules for each database instance.<br><br>
CHAPTER 6<br>
CONCLUSION<br>
6.1 introduction<br>
Technology is introducing new innovations day by day, thus reducing the time required
to do things. The proposed system can be used to reduce the time required to deliver
required blood to the needy in cases of emergency. The Android application can be used
by the people interested in donating their blood. The application provides a way of
communication and synchronization between the seekers and the blood donor. It also
provides them with the facility of communicating with the nearby donors in emergency.
The database is a vital aspect of the system. The Android application is developed using
Android Studio & Kotlin these are the open-source software, hence the system
developed is quite feasible.
<br><br>
6.2 Limitations<br>
There are some drawbacks and limitations in this software as it is a beta release and
under future development process.<br>
i. Need to install first on android before using.<br>
ii. Platform is not independent. So, it may not run on different operating systems
like iOS.<br>
iii. Some minor bugs exist<br>
iv. Limited features, need to explore.<br><br>
6.3 Future Goals<br>
In future, the above concept can be utilized for large scale blood plasma donation
management system. Further the application will be featured with the independent and
manual location tracking of donor and receiver, verification of the donor can be done
with more authenticated process. the message publication or the broadcasting of
advertisement process can be introduced in all the popular social media rather than only
on social websites like Facebook, WhatsApp, television radio etc.<br>
• We can update our user interface.<br>
• Adding chat option in our system for live communication.<br>
• We can also add chat bot services for notify every donor.<br>
• Add google map for patient exact location.<br>
<br><br>
