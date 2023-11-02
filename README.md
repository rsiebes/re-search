# re-search
Re-Search project - an efficient personalized search engine


*How we can become less dependent on commercial companies that handle the
bulk of our search queries?* 

Some observations about (commercial) search engines
 - Ranking algorithm is obscure
 - Filtering algorithm is obscure (i.e. which hits are removed a-priori)
 - Limited flexibility/options for search queries (e.g. no support for regex)
 - Limited personalisation (e.g. 'prioritize websites like this')
 - No anonymous personalisation (you have to share your profile to take advantage of the personalisation features)
 - No 'advanced'  views, for example to show different sets of ranked sites on controversial topics

Since it is almost impossible to compete with major search engines (due to their budget
of having billions worth server parks), the idea is

based on the following assumption: an individual most likely will be
interested/visit only a tiny fraction of the web during

his/her life. If we could kind of 'predict'/cluster this likely fraction
and store this in a Peer-to-Peer fashion (where each

user of the p2p search-engine infrastructure also hosts a part of the index for
other people, anonymously), we might get close to, or even beat the performance of 
commercial search engines.


To summarize: A distributed search engine, without centralized control
and anonymity built-in the protocol where the past, current and likely
future websites relevant to a user are indexed on the distributed index.

Peer-to-Peer technology is almost as old as the Web, and had a
'disruptive' reputation (like Napster for illegal file sharing), and got a

bit snowed-under by the cloud approach. However, censorship, commercial
and non-transparent content ranking algorithms,   and limited control
over search parameters are still relevant issues with most commercial
search engines, problems that successfully are addressed by various P2P
implementations.

As an inspiration we can have a look at YaCy: https://yacy.net/ , a
Content Addressable Network for storing a distributed index.

Since it is open source, with an active user - and - developer base, it
could be worthwhile to dive into the code and find out a way to achieve
anonymous collaborative filtering with content (ie website)
recommendations for indexing based on the search history of each user.
