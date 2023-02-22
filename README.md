# NetworkGraph
Run the Streamlit App
Network graphs (also called network diagrams) are a special type of visualization that shows the connections between a set of entities via nodes and edges. Each entity in the network graph is called a ‘node’ and the line connecting a pair of nodes is called an ‘edge’. An entity can be a person, an event, a sports team, or anything else. Network graphs are an effective way to visualize and analyze the relationships between entities within a network.

A network graph can be directed or undirected. The size and color of the nodes and the width of the edges can be used to show different attributes of the network entities and their relationships. Below is an example of a simple undirected network graph with the node colors representing the number of connections each node in the network.

generates interactive network graphs (like the one shown above) using Streamlit, NetworkX, and Plotly. The app allows users to upload a CSV file with their network data following certain formats — only two columns are required: one for source nodes and the other one for target nodes.

After users upload the data into the app, the app will generate an undirected network graph instantly with the color of the nodes representing the number of connections each node has in the network. Users can also choose different layout options for the graph or different color schemes for the nodes. Here is a short video demo of the app.
we can add more widgets to allow users to specify the size of the nodes or the width of the edges to convey more information about the network as well as the nodes’ and edges’ attributes. 
