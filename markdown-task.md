Welcome to **TreeLife**, your guide to learning about the beauty, diversity, and importance of trees around the world.

---
### About Us
At **TreeLife**, we're passionate about forests and green living.

Our mission is to:
- Educate people about the different types of trees.
- Promote sustainable forestry.
- Encourage reforestation projects.

```
"The best time to plant a tree was 20 years ago. The second best time is now."
```
>-*Chinese Proverb*


---

### Featured Trees
**Oak Tree**

**Scientific Name:** *Quercus robur*

Known for its strength and longevity, the oak is a symbol of endurance.
![](https://sites.dartmouth.edu/dujs/files/2020/11/EL-1.png)

---

### Pine Tree
**Scientific Name**: *Pinus*

Evergreen and aromatic, pine trees thrive in colder regions.
![](https://www.sciencing.com/sciencing/do-pine-trees-need-survive-6549613/c64512e361624e3d9a21ffc39aed7f5c.jpg)

---

### Tree Identification Tool
You can use this simple **Javascript** function to identify a tree by its characteristics:

```javascript
function identify_tree(leaf_shape, region){
    if(leaf_shape == "needle" && region == "cold"){
        return "Pine Tree"
    } else if(leaf_shape == "broad" && region == "temperate"){
        return "Oak Tree"
    } else {
        return "Unknown Tree"
    }
}
console.log(identify_tree("needle","cold"))
```