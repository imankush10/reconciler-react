Reconciler React

> Reconcilers, like the one in React, essentially compute the difference between the current State (data) and any new or updated State. By calculating the difference or diff like in git, they can selectively update DOM elements, eliminating the need to re-render the entire DOM.
Before React, dynamic websites were built using Vanilla JS or lower-level frameworks. In such cases, for every data change, the entire DOM is cleared and re-rendered to display this in the DOM based on the new data. The issue is that even minor data changes result in a complete DOM re-render, which is far from optimal.


The HTML and CSS section in this is fairly simple. It just contain a Title tag, Description tag and three buttons

Here the important part is that this program calculates the difference between the oldState and newState.
It also supports conditional rendering.
Instead of changing the entire DOM, it only renders the changes in the states i.e. diff just like react
