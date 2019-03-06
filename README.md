# just-testing-github

So you tell me I can have a table.

<table border="0">
  <thead>
    <tr><th>Some header text</th> <th>Some header text</th></tr>
  </thead>
  <tbody>
    <tr><td>Some body text</td> <td><img width="104px" src="https://storage.googleapis.com/modelzoo/tmp/activation-atlas/stickers/test.png"></td></tr>
  </tbody>
  <tfoot>
    <tr><td>Some footer text</td> <td>Some header text</td></tr>
  </tfoot>
</table>

And a `dl`?

<dl>
    <dt>Beast of Bodmin</dt>
    <dd>A large feline inhabiting Bodmin Moor.</dd>
    <dt><img width="104px" src="https://storage.googleapis.com/modelzoo/tmp/activation-atlas/stickers/test.png"></dt>
    <dd>A sea serpent.</dd>
    <dt>Owlman</dt>
    <dd>A giant owl-like creature.</dd>
</dl>


and a figure element?

<figure>
  <img width="104px" src="https://storage.googleapis.com/modelzoo/tmp/activation-atlas/stickers/test.png">
  <figcaption>Some figcaotion</figcaption>
</figure>

maybe we can abuse `display: initial` to get back inline-block behavior: edit turns out they never turned it off \o/

<div>
  <img width="104px" src="https://storage.googleapis.com/modelzoo/tmp/activation-atlas/stickers/test.png">
  <p>Attempt to get an inline block.</p>
</div>
