# from-Borra

# Greeshma Borra #

### Favorite Restaurant - Bawachi ###
This is the best restaurant in india which is famous for briyani and the taste was to good.

**Self Love is important**
**Kindness is about compassion and empathy** 
---
# Favourite Dishes
<ol>
<li>Dum Biryani</li>
<li>Chicken 65</li>
<li>Apricot Delight</li>
</Ol>

# Places near the restaurant
<ul>
<li>Mall</li>
<li>Park</li>
<li>Play station</li>
</ul>


Added link to [About Greeshma](MyMedia.md)
---

# Recommended Media

 In this table Iam recomending about book,song and vedio

| Name                  | Reason for Recommendation                | Creator                |
|-----------------------|------------------------------------------|------------------------|
| "The Alchemist"       | A timeless tale of self-discovery and destiny, guiding readers on a transformative journey. | Paulo Coelho           |
| "Bohemian Rhapsody" (Song) | A musical masterpiece that seamlessly weaves through various genres, showcasing Queen's artistic brilliance. | Queen (Freddie Mercury)|
| "Planet Earth II" (TV Series) | Breathtaking cinematography capturing the beauty and struggles of wildlife in diverse ecosystems. | David Attenborough     |
| "Inception" (Movie)   | A mind-bending cinematic experience that explores the layers of dreams and reality with stunning visuals. | Christopher Nolan      |

---
# Inspirational Quotes

> "Anyone who never made a mistake has never tried anything new" - *Albert Einstein*

> "You have to dream before your dreams come true" - *APJ Abdul Kalam*
---
# Code Fencing
Merge a series of lists into a list of lists. For example, [1, 2, 3] and [4, 5, 6] would merge into [[1, 2, 3], [4, 5, 6]].
```
def merge(*args, missing_val = None):
  max_length = max([len(lst) for lst in args])
  out_list = []

  for i in range(max_length):
    out_list.append([args[k][i] if i < len(args[k]) else missing_val for k in range(len(args))])

  return out_list 
  ```
  [Python Code Snippets](https://code.pieces.app/collections/python)
