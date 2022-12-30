# CSS Master Class

- HTML, CSS에 대해 공부하기 위한 클론코딩
- css의 flex, grid에 대해 자세하게 공부하기 위한 프로젝트

# 목차

- [Flex](#flex)
- [Grid](#grid)
- [Keywords Functions](#keywords-functions)
- [clone cording](#clone-cording)


# Flex

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

# Grid:

- 부모box에 사용.

| property | Image | info |
| -------- | ----- | ---- |
| grid-template-columns              | <img src="img/grid-template-columns.jpg" width="300"><br> | columns(세로)의 개수를 지정하는 방식이다.                                                                                                        |
| grid-template-rows                 | <img src="img/grid-template-rows.jpg" width="300"><br>    | rows(가로)의 개수를 지정하는 방식이다. ex) columns는 3개, rowssms 6개이다.                                                                       |
| grid-template-gap                  | <img src="img/grid-template-gap.jpg" width="300"><br>     | columns(세로)로 각각의 box마다 간격이다.                                                                                                         |
| grid-row-gap                       | <img src="img/grid-row-gap.jpg" width="300"><br>          | row(가로)로 각각의 box마다 간격이다.                                                                                                             |
| grid-gap                           | <img src="img/grid-gap.jpg" width="300"><br>              | column(세로), row(가로) 양쪽모두 각각의 box마다 간격이다.      grid-row-gap 와 grid-gap를 합친것.                                                |
| align-items     | <img src="img/grid-align-items.jpg" width="300"><br>    | grid의 자식box의 column을 기준으로 처음, 중간, 끝으로 옮길수 있다.|
| justify-items      | <img src="img/grid-justify-item.jpg" width="300"><br>    | grid의 자식box의  row를 기준으로 처음, 중간, 끝으로 옮길수 있다.        |
| place-items     | <br>    |  align-items 와 justify-items를 짧게 줄여서 사용 할 수 있다. ex) place-items : start  end  단 align-items가 앞이다. |
| align-content | <img src="img/grid-justify-content.jpg" width="300"><br>      | 부모box 전체의 colunm을 기준으로 처음,중간,끝으로 옮길수있다.  |
| align-contentt | <img src="img/grid-align-content.jpg" width="300"><br>      | 부모box 전체의 column을 기준으로 처음,중간,끝으로 옮길수있다.  |
| justify-content | <img src="img/grid-justify-content.jpg" width="300"><br>      | 부모box 전체의 row를 기준으로 처음,중간,끝으로 옮길수있다.  |
| grid-auto-rows | <img src="img/grid-auto-rows.jpg" width="300"><br>      | grid-template-rows를 통해 크기를 지정하지 않은 추가되는 row 부분들의 크기를 지정 하는 것 이다. 사진에선 9이후의 box들이다.   |
| grid-auto-columns | <img src="img/grid-auto-columns.jpg" width="300"><br>      | grid-template-columns를 통해 크기를 지정하지 않은 추가되는 columns 부분들의 크기를 지정 하는 것 이다. 사진에선 9이후의 box들이다. 단 주의할점은 default값은 추가되는 box들은 row에 추가가 된다. 따라서 column으로 추가되도록 할려면 grid-auto-flow:column을 설정을 해줘야 한다. |



<hr>
<br>
자식box에 사용

| property                           | Image                                                     | info                                                                                                                                             |
| ---------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| grid-template-areas                | <img src="img/grid-template-areas.jpg" width="300"><br>   | 원하는 layout을 작성할수 있도록 한다.   단 자식box에 template-area의 이름을 지정해줘야 한다.                                                     |
| grid-column-start, grid-column-row | <img src="img/grid-column-start,end.jpg" width="300"><br> | grid의 column부분을 위치를 통해 지정할 수 있다.    사진의 숫자는 column의 start,end의 의미이다. 짧게 grid-column : 1/2 이런식으로 사용 가능하다. |
| grid-row-start, grid-row-row       | <img src="img/grid-row-start,end.jpg" width="300"><br>    | grid의 row부분의 위치를 통해 지정할 수 있다.    사진의 숫자는 row의 start,end의 의미이다. 짧게 grid-row : 1/2 이런식으로 사용 가능하다.          |
| align-self                         | <img src="img/grid-align-self.jpg" width="300"><br>       | grid의 자식 box의 기준으로 column부분을 지정할 수 있다.                                                                                          |
| justify-self                       | <img src="img/grid-justtify-self.jpg" width="300"><br>    | grid의 자식 box의 기준으로 row부분을 지정할 수 있다.                                                                                             |



# Keywords Functions

| Keywords & Functions | Where                                                   | How To                                                          | What                                                                                         | img                                           |
| -------------------- | ------------------------------------------------------- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | --------------------------------------------- |
| repeat               | 주로 grid-template-rows or grid-template-columns에 사용 | grid-template-rows: repeat(1, 500px)                            | 1fr 1fr 1fr 과 같이 크기를 정할때 반복되는 부분을 함수로 사용하는 것이다. ex) repeat(3, 1fr) |
| fr                   | 주로 grid-template-rows or grid-template-columns에 사용 | grid-template-rows: repeat(1, 1fr)                              | frational unit 으로, 사용가능한 공간에 대한 비율을 의미한다.                                 |
| minmax               | 주로 grid-template-rows or grid-template-columns에 사용 | grid-template-rows: repeat(10, minmax(100px, 1fr))              | property중 하나로서 최소 최대 크기를 지정한다.                                               |
| auto-fit             | 주로 grid-template-rows or grid-template-columns에 사용 | grid-template-rows: repeat(auto-fit, minmax(100px, 1fr))        | 현재의 element를 늘려서 사용 공간을 꽉 채우는 것이다.                                        | <img src="img/auto-fit.jpg" width="1000"><br> |
| auto-fill            | 주로 grid-template-rows or grid-template-columns에 사용 | grid-template-rows: repeat(auto-fill, minmax(100px, 1fr))       | 현재의 element의 크기로 균등하게 사용공간을 채우는 것이다.                                   | <img src="img/auto-fit.jpg" width="1000"><br> |
| min-content          | 주로 grid-template-rows or grid-template-columns에 사용 | grid-template-rows: repeat(auto-fill, minmax(min-content, 1fr)) | box의 내용물의 따라 최소한의 크기를 지정하는 것이다.                                         |                                               |
| max-content          | 주로 grid-template-rows or grid-template-columns에 사용 | grid-template-rows: repeat(auto-fill, minmax(max-content, 1fr)) | box의 내용물의 따라 최대한의 크기를 지정하는 것이다.                                         |                                               |


# Clone cording

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
