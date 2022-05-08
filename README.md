# SCSS Masterclass
(S)CSS Layout Masterclass: Flexbox & Grid
## Flexbox:


| property                | Image                                                                                                                                                                                           | info                                                                                                     |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| flex-direction : row    | <img src="img/direction-row.jpg" width="300"><br>                                                                                                                                               | default값이며, Main Axis는 수평(가로), Cross Axis는 수직(세로)이다.                                      |
| flex-direction : column | <img src="img/direction-column.jpg" width="300"><br>                                                                                                                                            | Main Axis는 수직(세로), Cross Axis는 수평(가로)이다.                                                     |
| order                   | <img src="img/order.jpg" width="300"><br>                                                                                                                                                       | 자식 box에 적용하며, 자식box의 순서를 변경 할 수 있다.                                                   |
| justify-content         | <img src="img/justify-content.jpg" width="300"><br>                                                                                                                                             | Main Axis측으로 움직이며 부모 box에 설정해준다.                                                          |
| align-items             | <img src="img/align-items.jpg" width="300"><br>                                                                                                                                                 | Cross Axis에 측으로 움직이며, 부모 box에 설정해준다.                                                     |
| align-self              | <img src="img/align-self.jpg" width="300"><br>                                                                                                                                                  | 자식 box에 적용, 지정한 자식box의 cross Axis부분의 위치를 조절한다.                                      |
| flex-nowrap             | <img src="img/nowrap.jpg" width="300"><br>                                                                                                                                                      | Default 값이며 부모box에 지정하고, 자식box의 넓이에 상관없이 flex-box에 채운다.                          |
| flex-wrap               | <img src="img/wrap.jpg" width="300"><br>                                                                                                                                                        | 부모box에 지정하고, flex-box에 상관없이 자식 box의 넓이를 우선으로 채운다.                               |
| align-content           | <default값><img src="img/align-content.jpg" width="300"><br>  <center값> <img src="img/content-center.jpg" width="300"><br>   <flex-end값> <img src="img/content-flex-end.jpg" width="300"><br> | 부모box에 지정하고, 자식 box의 줄 간격을 조절 할 수 있다.                                                |
| flex-grow               | <img src="img/flex-grow.jpg" width="300"><br>                                                                                                                                                   | 자식 box에 지정하며, 화면이 커짐에 따라 지정한 자식 box의 크기 비율을 조절할 수 있다.                    |
| flex-shirink            | <img src="img/flex-shirink.jpg" width="300"><br>                                                                                                                                                | 자식 box에 지정하며, 화면이 작아짐에 따라 지정한 자식 box의 크기 비율을 조절할 수 있다.                  |
| flex-basis              | <img src="img/flex-basis.jpg" width="300"><br>                                                                                                                                                  | 자식 box에 지정하며, flex-grow, flex-shrink로 변형이 되기 전 처음 크기를 나타내며, Main Axis에 적용된다. |


<hr>
<br>
<br>
<br>

## Grid:

| property                           | Image                                                     | info                                                                                                                                             |
| ---------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| grid-template-columns              | <img src="img/grid-template-columns.jpg" width="300"><br> | columns(세로)의 개수를 지정하는 방식이다.                                                                                                        |
| grid-template-rows                 | <img src="img/grid-template-rows.jpg" width="300"><br>    | rows(가로)의 개수를 지정하는 방식이다. ex) columns는 3개, rowssms 6개이다.                                                                       |
| grid-template-gap                  | <img src="img/grid-template-gap.jpg" width="300"><br>     | columns(세로)로 각각의 box마다 간격이다.                                                                                                         |
| grid-row-gap                       | <img src="img/grid-row-gap.jpg" width="300"><br>          | row(가로)로 각각의 box마다 간격이다.                                                                                                             |
| grid-gap                           | <img src="img/grid-gap.jpg" width="300"><br>              | column(세로), row(가로) 양쪽모두 각각의 box마다 간격이다.      grid-row-gap 와 grid-gap를 합친것.                                                |
| grid-template-areas                | <img src="img/grid-template-areas.jpg" width="300"><br>   | 원하는 layout을 작성할수 있도록 한다.   단 자식box에 template-area의 이름을 지정해줘야 한다.                                                     |
| grid-column-start, grid-column-row | <img src="img/grid-column-start,end.jpg" width="300"><br> | grid의 column부분을 위치를 통해 지정할 수 있다.    사진의 숫자는 column의 start,end의 의미이다. 짧게 grid-column : 1/2 이런식으로 사용 가능하다. |
| grid-row-start, grid-row-row       | <img src="img/grid-row-start,end.jpg" width="300"><br>    | grid의 row부분의 위치를 통해 지정할 수 있다.    사진의 숫자는 row의 start,end의 의미이다. 짧게 grid-row : 1/2 이런식으로 사용 가능하다.          |





- [x] justify-items
- [x] align-items
- [x] place-items
- [x] justify-content
- [x] align-content
- [x] grid-auto-columns
- [x] grid-auto-rows
- [x] grid-auto-flow
- [x] justify-self
- [x] align-self

### Keywords & Functions:

- [x] repeat
- [x] fr
- [x] minmax
- [x] auto-fit
- [x] auto-fill
- [x] min-content
- [x] max-content

## SCSS:

- [x] Variables
- [x] Nesting
- [x] Mixins
- [x] Extend
- [x] Responsive Mixins


## clone cording:

- [x] [https://besthorrorscenes.com/](https://besthorrorscenes.com/)
- [x] [https://paint-box.com/](https://paint-box.com/)
- [x] [http://10x19.co/](http://10x19.co/)
- [x] [http://www.z-o-o.fr/](http://www.z-o-o.fr/)
- [x] [https://schwartzmedia.com.au/](https://schwartzmedia.com.au/)
- [x] [https://tolv.dk/](https://tolv.dk/)
- [x] [https://rodicdavidson.co.uk/](https://rodicdavidson.co.uk/)
- [x] [https://beige.de/](https://beige.de/)
- [x] [http://donicaida.com/](http://donicaida.com/)
- [x] [https://wonhundred.com/](https://wonhundred.com/)
- [x] [https://canalstreet.market/](https://canalstreet.market/)