<h1>Administration</h1>
<h2>How can we send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, rather than treat them as pass-through intermediaries?</h2>
In the header of the card, we can write the id of the node followed by the command. When the node reads the card and the id's match, it will run the command that it written.