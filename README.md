<div class="container-fluid">
  <form>
    <div class="form-group row">
      <label class="col col-sm-4 col-form-label" for="colors">Color</label>
      <div class="col col-sm-4">
        <select name="colors" id="colors" class="form-control">
          <option selected>Select...</option>
          <option value="blue">Blue</option>
          <option value="red">Red</option>
          <option value="yellow">Yellow</option>
          <opion value="Green">Green</option>
        </select>
      </div>
    </div>
<!-- Above this is the section for you to edit -->
    <div class="form-group row">
      <div class="col">
        <button type="button" class="btn btn-primary" onclick="changeColor()">Go</button>
      </div>
    </div>
  </form>
</div>


<hr />
<h1>Your Challenge:</h1>
<p>You will only need to change the code in the HTML section of this Codepen, above the line with the comment that says "Above this is the section for you to edit".</p>
<ol>
  <li>
    For both the "col" class in the label element and the "col" class for the div that wraps around the select element, modify them so that they each take up 1/3rd of the row for small and up viewports.
  </li>
  <li>
    Beneath the option "Blue", add two or more new color options of your choice. Make sure that the "value" holds a CSS color value such as "red" or "#fff". 
  </li>
  <li>
    Clicking on the label text "Color" should cause the Select input to become active, but currently, it does not. Can you figure out why, and how to fix it?
  </li>
  <li>
    Verify that if you choose a color and click on the "Go" button, the background color changes to the color you selected.
  </li>
</ol>

<br />
<hr />
<h1>Resources</h1>
<ul>
  <li>
    <a href="https://getbootstrap.com/docs/4.5/components/forms/" target="_blank">Bootstrap Forms</a>
  </li>
  <li>
    <a href="https://getbootstrap.com/docs/4.5/components/forms/#form-controls" target="_blank">Bootstrap Form Controls</a>
  </li>
  <li>
    <a href="https://getbootstrap.com/docs/4.5/layout/grid/" target="_blank">Bootstrap Grid</a>
  </li>
  <li>
    W3Schools - <a href="https://www.w3schools.com/tags/tag_select.asp" target="_blank">&lt;select&gt;</a> and <a href="https://www.w3schools.com/tags/tag_option.asp" target="_blank">&lt;option&gt;</a>
  </li>
  <li>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label" target="_blank">MDN - Label</a>
  </li>  
</ul>
