---
title: Sample Page
description: This is meta description

---
### Table title

| Header | Header | Header |
| --- | --- | --- |
| Cell | Cell | Cell |
| Cell | Cell | Cell |
| Cell | Cell | Cell |

### Here is a youtube video

{{< youtube w7Ft2ymGmfc >}}

    <style>
    
      .ex8 .parent {
        height: auto;
        display: grid;
        grid-gap: 1rem;
        grid-template-columns: repeat(3, 1fr);
      }
    
      .ex8 .visual {
        height: 100px;
        width: 100%;
      }
    
      .ex8 .card {
        display: flex;
        flex-direction: column;
        padding: 1rem;
        justify-content: space-between;
      }
    
      .ex8 h3 {
        margin: 0
      }
    </style>
     <div class="parent white">
        <div class="card yellow">
          <h3>Title - Card 1</h3>
          <p contenteditable>Medium length description with a few more words here.</p>
          <div class="visual pink"></div>
        </div>
        <div class="card yellow">
          <h3>Title - Card 2</h3>
          <p contenteditable>Long Description. Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
          <div class="visual blue"></div>
        </div>
        <div class="card yellow">
          <h3>Title - Card 3</h3>
          <p contenteditable>Short Description.</p>
          <div class="visual green"></div>
        </div>
      </div>