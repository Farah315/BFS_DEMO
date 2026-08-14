SNAP Facebook Ego Network — Real Dataset
==========================================
Source: Stanford SNAP (McAuley & Leskovec, "Learning to Discover Social Circles
in Ego Networks", NIPS 2012)
https://snap.stanford.edu/data/ego-Facebook.html

facebook_combined.txt   -> raw edge list, full real dataset (each line = one real friendship)
facebook_edges_full.csv -> same edges, CSV format (source,target)
facebook_nodes_full.csv -> node list with degree, CSV format
facebook_subgraph.json  -> smaller real subgraph (95 nodes) sampled around an actual
                           distance-5 shortest path, ready for browser visualization

Verified stats (computed directly from the file, not estimates):
  Nodes: 4,039
  Edges: 88,234
  Average shortest path length: 3.693
  Diameter: 8
  Connected: yes (single component)
