# assignment2-coats

# Logan Coats

## LC's Hamburger's
Its kinda the <b>best place</b> to get burgers in Kansas City. It's in <b>Platte Woods</b>, south of Barry Road and North of NW 72nd street, right next to I-29.

***
### Directions from KCI Airport

<ol>
<li>Exit the airport onto I-29 south.</li>
<li>Exit I-29 South at the NW 72nd Street exit.</li>
<li>Turn right onto NW 72nd Street, then turn right again onto NW Prairie View Road.</li>
<li>Turn right on NW Spur Dr. and enter the LC's Hamburgers parking lot on the right.</li>
</ol>
<ul>

#### Things I'd recommend:
<li>Hamburger</li>
<li>Big Deal (Cheeseburger w/grilled onions, a regular fry and drink</li>
<li>Double Bacon Cheeseburger</li>
<li>Chocolate Shake</li>
</ul>

***
### Sports and Activities I'd recommend:
These are things I like to do/play and I thought I would share them here.
| Name of activity | Location                   | Cost   | 
| :---             |   :---:                    | ---:   |
| Tennis           | Courts by rec. center      | 30$    |
| Disc Golf        | Disc golf course on campus | 25-30$ |
| Ping Pong        | Rec. Center, The Station   | <10$   |
| Gaming           | Anywhere with internet     | 100$+  |

***
### Quotes

> What is better? To be born good or to overcome your evil nature through great effort? - *Paarthunax, ESV: Skyrim*

> Lack of something to feel important about is almost the greatest tragedy a man may have. - *Arthur Morgan, Red Dead Redemption II*

***
### Depth First Search Algorithm

> Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. - [Wikipedia](https://en.wikipedia.org/wiki/Depth-first_search#:~:text=Depth%2Dfirst%20search%20(DFS),along%20each%20branch%20before%20backtracking.)

```cpp
vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices

vector<bool> visited;

void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}
```
[Code Source](https://cp-algorithms.com/graph/depth-first-search.html)

[About me](AboutMe.md)