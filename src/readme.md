#CSS 강의 정리
 - 페이지를 볼때 "박스를 나눠서 보는 눈"을 가져야 한다.

-> 모두 div로 나누는것 보다는 header, nav, footer, section, article 등으로 
나누는 것이 더 좋다.

cf) article 은 여러가지 내용을 그룹화 해서 재사용이 가능한 애들을 주로 작성

### Block vs Inline
Block은 한줄에 하나

Inline은 공간이 허용하면 다른 태그 옆에 배치가 가능!

화면을 나눠볼때 BOX 와 ITEM 으로 나눠서 볼 수 있다.

BOX는 기본적으로 사용자에게 보여지지 않는다.

<table>
    <thead>
        <tr>
            <td>BOX (사용자에게 보여지지 않는 태그들)</td>
            <td>ITEM (사용자에게 보여지는 태그들)</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                header , section
                footer, article<br />
                nav, div, aside, span <br />
                main, form
            </td>
            <td>
                a, video, button, audio <br />
                input, map, label, canvas <br />
                img, table
            </td>
        </tr>
    </tbody>
</table>


<table>
    <thead>
        <tr>
            <td>Block</td>
            <td>Inline</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                한줄에 하나
            </td>
            <td>
                공간이 허용하면 다른 태그 옆에 배치가 가능
            </td>
        </tr>
    </tbody>
</table>

