# Bootstrap Survey Form

A collection of survey forms built with the latest Bootstrap 5. Choose from a variety of pre-made surveys, such as multiple choice survey, checkbox survey, modal survey and many more.

## Basic example

#### Multiple choice survey
Allow respondents to select one or more options from a list of answers that you define within radio buttons or checkboxes.

```html
<div class="row col-5">
  <h4 class="fw-bold text-center mt-3"></h4>
  <form class=" bg-white px-4" action="">
    <p class="fw-bold">How satisfied are you with our product?</p>
    <div class="form-check mb-2">
      <input class="form-check-input" type="radio" name="exampleForm" id="radioExample1" />
      <label class="form-check-label" for="radioExample1">
        Option 1
      </label>
    </div>
    <div class="form-check mb-2">
      <input class="form-check-input" type="radio" name="exampleForm" id="radioExample2" />
      <label class="form-check-label" for="radioExample2">
        Option 2
      </label>
    </div>
    <div class="form-check mb-2">
      <input class="form-check-input" type="radio" name="exampleForm" id="radioExample3" />
      <label class="form-check-label" for="radioExample3">
        Option 3
      </label>
    </div>
  </form>
  <div class="text-end">
    <button type="button" class="btn btn-primary">Submit</button>
  </div>
</div>
```

#### Much more examples and a detailed description can be found at [📄 Survey form documentation page](https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/)
