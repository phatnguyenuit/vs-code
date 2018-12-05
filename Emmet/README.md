# Emmet

## Notice

### HTML

```html
<!-- Note: using alias: bq for blockquote, lorem generator: lorem10 for generating 10 words -->
<!-- bq.blockquote.text-right>p.mb-0>lorem10^footer.blockquote-footer>{Someone famous in }+cite[title="Source Title"]{Source Title} -->
<blockquote class="blockquote text-right">
  <p class="mb-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam, quibusdam.</p>
  <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>

<!-- Note: using implicit tag names (tr inside thead and tbody; td inside tr) and multiplication * -->
<!-- table.table>thead>.table-row>th*3^^tbody>.table-row*2>.table-cell*3 -->
<table class="table">
  <thead>
    <tr class="table-row">
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr class="table-row">
      <td class="table-cell"></td>
      <td class="table-cell"></td>
      <td class="table-cell"></td>
    </tr>
    <tr class="table-row">
      <td class="table-cell"></td>
      <td class="table-cell"></td>
      <td class="table-cell"></td>
    </tr>
  </tbody>
</table>

<!-- Note: using sibling of text element -->
<!-- h2>{Example header }+span.badge.badge-secondary{New} -->
<h2>Example header <span class="badge badge-secondary">New</span></h2>

<!-- Note: using multiplication *, climbing-up ^, item numbering $ and implicit tag names (li inside ol) -->
<!-- nav>ol.breadcrumb>.breadcrumb-item*2>a{Level #$$}^.breadcrumb-item.active{Data} -->
<nav>
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="">Level #01</a></li>
    <li class="breadcrumb-item"><a href="">Level #02</a></li>
    <li class="breadcrumb-item active">Data</li>
  </ol>
</nav>

<!-- Note: using muliplication * and implicit tag names (div) -->
<!-- .btn-group[role=group aria-label="Basic example"]>button.btn.btn-secondary[type=button]*3 -->
<div class="btn-group" role="group" aria-label="Basic example">
  <button class="btn btn-secondary" type="button"></button>
  <button class="btn btn-secondary" type="button"></button>
  <button class="btn btn-secondary" type="button"></button>
</div>

<!-- Note: using implicit tag names (option inside select), multiplication * and item numbering $ -->
<!-- select#selectItem.form-control[multiple]>[value=$]*3{Item $$} -->
<select name="" id="selectItem" class="form-control" multiple="multiple">
  <option value="1">Item 01</option>
  <option value="2">Item 02</option>
  <option value="3">Item 03</option>
</select>

<!-- Note: using grouping (), snippets form:get, input:search -->
<!-- form:get#searchForm>(.form-group>label+input:search#search.form-control[placeholder=search])+button:submit.btn.btn-primary{Search} -->
<form action="" method="get" id="searchForm">
  <div class="form-group"><label for=""></label><input type="search" name="" id="search" class="form-control" placeholder="search"></div>
  <button type="submit" class="btn btn-primary">Search</button>
</form>
```

## References

1. [Emmet in Visual Studio Code](https://code.visualstudio.com/docs/editor/emmet)

1. [Emmet Documentation](https://docs.emmet.io/)

1. [Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)