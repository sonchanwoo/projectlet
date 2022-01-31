

```jsp
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css" />
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css" />
<script	src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>

<div class='row'>
	<div class="pull-right">
		<ul class="pagination">

			<c:if test="">
				<li class="paginate_button previous"><a
					href="">Previous</a></li>
			</c:if>

			<c:forEach var="num" begin=""
				end="">
				<li class="paginate_button">
					<a href="">2</a>
				</li>
			</c:forEach>

			<c:if test="">
				<li class="paginate_button next"><a
					href="">Next</a></li>
			</c:if>
			
		</ul>
	</div>
</div>
```