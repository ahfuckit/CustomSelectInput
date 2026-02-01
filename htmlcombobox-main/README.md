![image](https://github.com/user-attachments/assets/f24c961c-3bb5-47de-af9e-47ebcc89e776)
**![image](https://github.com/user-attachments/assets/dd3a6399-8903-4e76-9875-0455196c7379)**

**![gif](https://github.com/user-attachments/assets/2e998c3a-6689-4354-ae07-a09aaa5aef8c)**


```html

<form id="aform">
    <combo-input name="comboinput" data-placeholder="Type or select" data-options=":'',value:text,valuetext"></combo-input>
    <button type="submit">Submit</button>
    <!-- your other inputs -->
</form>
<script src="https://csingendonk.github.io/lua/comboinput.js"></script>

```
<section>  <h4>Documentation</h4>   <div class="docs-content">  <h5>HTML Attributes</h5>    <div class="attribute">data-options</div>  <ul>  <li>Simple array format:  <div class="example">  <code>&lt;combo-input data-options="[a,b,c]"&gt;</code>  </div>  </li>  <li>Value-text pairs:  <div class="example">  <code>[a:1,b:2,c:3]</code>  </div>  </li>  <li>Mixed Array format:  <div class="example">  <code>[[a,1,b:2,c:'','':3]]</code>  </div>  </li>  <li>Mixed Array Result:  <code>[{"value":"a","text":"a"},{"value":"1", "text":"1"},{"value":"b","text":"2"},{"value":"c","text":""},{"value":"", "text":"c"}]</code>  </li>  </ul>   <div class="attribute">data-value</div>  <ul>  <li>Sets the pre-selected value for the component  <sup>Should have a value in the data-options array</sup>  </li>  </ul>   <div class="attribute">data-placeholder</div>  <ul>  <li>Text to display when no value is selected</li>  </ul>   <div class="attribute">data-style</div>  <ul>  <li>Selectors:  <ul>  <li>input - Default view styling</li>  <li>select - Dropdown menu styling</li>  <li>div - Container styling</li>  </ul>  </li>  <li>Format options:  <div class="example">  <code>{"div": {"color": "red"}, "input": {"border": "1px solid"}}</code>  </div>  </li>  </ul>  </div>  </section>`;

#note: 
- In order to use this like any text input inside of a form element,
   the name="" attribute on the combo-input,
   and the id="" attribute on the form containing it,
  *MUST have a value*
   any value, but a value nonetheless.
- &lt;label&gt; optional.

```javascript
CustomSelectInput.createComboInput());
```
![image](https://github.com/user-attachments/assets/79a9be2d-bbec-4051-ae97-be5a7bd8c636)
