Welcome to **TreeLife**, your guide to learning about the beauty, diversity, and importance of trees around the world.

---

# About Us

At **TreeLife**, we're passionate about forests and green living.

Our mission is to:
- Educate people about the different types of trees.
- Promote sustainable forestry.
- Encourage reforestation projects.

> "The best time to plant a tree was 20 years ago. The second best time is now." — *Chinese Proverb*


---

## Featured Trees

### Oak Tree

**Scientific Name**: *Quercus robur*

Known for its strength and longevity, the oak is a symbol of endurance.

![](https://bpb-us-e1.wpmucdn.com/sites.dartmouth.edu/dist/0/2024/files/2020/11/EL-1.png)

---

### Pine Tree

**Scientific Name**: *Pinus*

Evergreen and aromatic, pine trees thrive in colder regions.

![](https://upload.wikimedia.org/wikipedia/commons/0/07/Bristlecone_pinus_longaeva_bristly_cone.jpg)

---

## Tree Identification Tool

You can use this simple **Javascript** function to identify a tree by its characteristics:

```
function identify_tree(leaft_shape, region){
    if (leaf_shape == "needle" && region == "cold"){
        return "PineTree"
    } else if(leaf_shape == "broad" && region == "temperate"){
        return "Oak Tree"
    } else {
        return "Unkown Tree"
    }
    
}
console.log(identify_tree("needle", "cold"))
```