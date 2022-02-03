# horizontal-weSite-engine

Moteur de scrolling horizontal


<br>
<hr>


## Mise en place

  Définie le nom cible pour associé le container et les élement enfants du slide

  ```javascript
      Default value : horizontalScroll
  ```

  Dans votre fichier HTML
  ```HTML

    <Container horizontalScroll>

      <ChildContainer silde="horizontalScroll"></ChildContainer>
      <ChildContainer silde="horizontalScroll"></ChildContainer>
      <ChildContainer silde="horizontalScroll"></ChildContainer>
      [...]

    </Container>

  ```

  <br>
<hr>

## Paramètres

   ```js
        slideXWithMouseWheel: true,
        sliderName: "hs",
        currentSlide: 0,
        infiniteLoop: true,
        slideWidth: 95,
        slideTransition: "0.3",
        slideLink: true,
        jumpLink: false,
        pushUp: false,
        puhsDown: false,
        linkClassName: "linkSlideHorizontal",
   
   ```



