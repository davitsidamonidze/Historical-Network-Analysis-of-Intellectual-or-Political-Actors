# Historical-Network-Analysis-of-Intellectual-or-Political-Actors
caucasus-intellectual-networks
import networkx as nx
import matplotlib.pyplot as plt

G = nx.Graph()

edges = [
("Ilia Chavchavadze","Tbilisi State University"),
("Ivane Javakhishvili","Tbilisi State University"),
("Ilia Chavchavadze","National Movement"),
("Ivane Javakhishvili","National Movement")
]

G.add_edges_from(edges)

nx.draw(
G,
with_labels=True,
node_size=2500
)

plt.show()
