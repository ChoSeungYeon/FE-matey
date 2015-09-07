# rowspan에 대처가능한 테이블 만들기
### 설명
```
데이터 테이블내의 셀들이 rowspan으로 인한 병합이 이루어 졌을 때,   
border에 영향을 주지 않는 테이블을 만듭니다.  

과제 내용이 이해하기 어려우시면 아래 이미지의 표와 똑같은 표를 만드시면됩니다.
```
![완성 테이블](images/sample01.png)

### 대응
1. css3, JavaScript, jQuery를 사용하지 않습니다. ( IE8 )  
2. 테이블의 양쪽에는 border가 없으며, border의 px은 1px 입니다.  
3. table 태그를 제외한 어떤 태그에도 id, class, 어떤 속성도 추가하지 않습니다.  
4. data 형식의 테이블 과제이기 때문에 tbody에 th가 있습니다.  

### 소스
```html
<table class="">
	<thead>
		<tr>
			<th>th</th>
				"
				"
		</tr>
	</thead>
	<tbody>
		<tr>
			<th>th</th>
			<td>td</td>
				"
				"
		</tr>
	</tbody>
</table>
```