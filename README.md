**# grp_project

A new Flutter project.

## Getting Started

Introduction of our group project :

Being a parent is an amazing adventure full of rewards and difficulties; the path can be particularly 
difficult for parents of autistic children. A major worry was revealed in 2021 by an eye-opening 
study conducted by the Centre of Occupational Therapy: an amazing 82.0% of parents of children with
autism reported feeling a great deal of stress. This figure clearly illustrates the extreme challenges 
and stress these families are under. It can be difficult to meet the special demands of kids on the
autism spectrum, and doing so frequently has a negative impact on parents' and carers' mental health.

Acknowledging the critical role that assistance plays in overcoming these challenges, creative 
approaches have surfaced to reduce anxiety and improve autism care. The difficulties and complexities 
of raising autistic children have led to a rise of innovative treatments and technology designed to 
lessen the load on parents and enhance the quality of life for these amazing kids. New technologies 
 have appeared in this environment of innovation and support, providing potential paths 
for comprehending and assisting children with autism. In addition to offering comfort, the goal of 
this innovative age is to empower parents and carers and provide a more welcoming and encouraging 
atmosphere for families navigating the challenges associated with autism.



Problem Statement :

- Parents often lack sufficient knowledge and resources to effectively manage and support children 
with special needs, complicating their ability to navigate diverse situations.
- Children with special needs, particularly those prone to hyperactivity and tantrums, struggle due 
to insufficient understanding of triggers from their environment, emotions, and specific situations.
- The lack of understanding and support leads to complexity in managing the moods and needs of these 
children, causing difficulties for both parents and educators.

Objective :

- To identify the environmental surrounding using sensors that trigger autism tantrums.
- To monitor the emotional dysregulation of the autism kids to improve tantrum management.
- To provide a platform for parents and educators regarding the autism spectrum disorder community to collaborate.


Database used : Firebase 

Our group project uses Firebase Firestore to immediately store activity-level data inserted by the 
parents in the system. Within the Firebase, Firestore is a NoSQL document-based database that may 
be used to store structured data in the form of documents and collections. Parents enter 
activity-level information on their children's actions or behaviours using an interface connected to 
Firebase Firestore. To directly insert this data into the Firestore database, the interface 
communicates with Firebase Firestore's API. The information contains the child’s behaviour toward 
the triggers, date, location, and what happened before and after the triggers.

The table that are used are : 
1) chats
2) comments
3) educators
4) feedback
5) feeds
6) likes
7) mood
8) parents
9) system_log
10) users
