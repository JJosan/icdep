<h1>Anti Duplication</h1>
<h2>How can we ensure that each card is received once and only once?</h2>
In the header of each card, we can write down an unique ids. when the cards reach the destination node, it can keep track of which cards have already been recieved and when it sees that there is a duplicate, it will throw the card away.