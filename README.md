This project involves the implementation of the concepts of Graph Theory to analyse the famous play - Julius Caesar written by William Shakespeare. 
"Julius Caesar" by William Shakespeare is a timeless tragedy that delves into the complexities of power, betrayal, and political upheaval in ancient Rome. Set against a backdrop of conspiracy and ambition, the play unfolds as political leaders grapple with their loyalties and personal agendas. Brutus, torn between friendship and duty, ultimately succumbs to the conspirators' plot to assassinate Caesar. The aftermath sees Rome plunged into chaos, with Mark Antony stirring the masses against Brutus and his co-conspirators. The play masterfully explores themes of honor, manipulation, and the consequences of unchecked political ambition, making it a compelling exploration of human nature and societal dynamics.

The protagonists of the story are - ['cassius','brutus','lucilius','octavius','antony','messala','strato','clitus','dardanius','cato','messenger', 'varro','claudio','lucius','ghost','poet','lepidus','cinna','servant','decius','casca','popilius','publius', 'artemidorus','soothsayer','portia','calpurnia','caesar','ligarius','trebonius','cicero','flavius','marullus']

Centrality measures in network analysis provide insights into the importance or prominence of nodes (characters, in the context of a novel) within a network. While "centrality measures" are often used in the analysis of social networks or graph theory, the application to characters in a novel is more metaphorical and interpretive.

Degree Centrality: Interpretation: Characters with high degree centrality interact with many other characters. They may be central to the story, having multiple connections and relationships.

Betweenness Centrality: Interpretation: Characters with high betweenness centrality may act as bridges between different groups or storylines. They play a crucial role in connecting disparate parts of the narrative.

Closeness Centrality: Interpretation: Characters with high closeness centrality are close or easily reachable by other characters. They may be influential or have a strong impact on the narrative due to their proximity to others.

PageRank Centrality: Interpretation: PageRank reflects the importance of characters who are connected to other important characters. It measures a character's "popularity" in the network.

We have observed that for all characters - Degree centrality = 1.0, Betweeness Centrality = 0.0, Closeness Centrality = 1.0

This means that -

Degree Centrality: 1.0 Interpretation: A degree centrality of 1.0 means that the character is directly connected to all other characters in the network. They have the maximum number of connections possible. In the context of a novel, this character interacts with every other character, making them central to the overall narrative.

Betweenness Centrality: 0.0 Interpretation: A betweenness centrality of 0.0 indicates that the character's presence is not crucial for maintaining connections between other characters. They don't act as a bridge or intermediary between different groups of characters. In other words, the character's absence wouldn't significantly alter the communication flow in the network.

Closeness Centrality: 1.0 Interpretation: A closeness centrality of 1.0 means that the character is very close to all other characters in terms of the shortest paths. They can reach any other character in the network quickly. This could suggest that the character is emotionally or physically close to others in the narrative, making them readily accessible or influential.

From the Pagerank centrality values it can be noted that Caesar, Brutus, Cassius and Lucius are the most important characters and the least important characters are Ghost of Caesar, Cato, Soothsayer

In the context of a novel, the social graph derived from character interactions is a fictional representation rather than a depiction of real-world social relationships. The relationships and connections among characters are crafted by the author for the purpose of storytelling. While the social graph may exhibit certain properties reminiscent of real-world graphs, it is fundamentally a product of fiction.

Properties of Real-World Graphs:

Small World Phenomenon: Real-world social networks often exhibit the small-world property, where most nodes can be reached from every other node by a small number of steps. In a novel, this might be reflected in characters having relatively few intermediary characters between them, allowing for interconnected storylines.

Scale-Free Network: Real-world social networks often follow a scale-free distribution, meaning that a few nodes have significantly more connections than others. In a novel, major characters might have a higher degree of connectivity, analogous to influential individuals in real-world networks.

Community Structure: Social networks tend to have community structures, where nodes form clusters with higher internal connectivity. Similarly, in a novel, characters may form groups or communities based on shared interests, alliances, or conflicts.

Centrality Measures: Certain characters may play central roles in the narrative, similar to influential individuals in real-world networks. For example, a protagonist might have high degree centrality, interacting with various other characters.

Having the value as 0.0 for the betweeness centrality implies that there's no character which is not visible and yet plays an important role in the plot.
