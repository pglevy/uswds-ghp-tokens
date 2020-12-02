---
title: Form controls
---
## Character count
<form class="usa-form">
  <div class="usa-character-count">
    <div class="usa-form-group">
      <label class="usa-label" for="with-hint-input">
        Text input
      </label>
      <span id="with-hint-input-hint" class="usa-hint">
        This is an input with a character counter.
      </span>
      <input class="usa-input usa-character-count__field" id="with-hint-input" maxlength="25" name="with-hint-input" aria-describedby="with-hint-input-info with-hint-input-hint">
    </div>
    <span id="with-hint-input-info" class="usa-hint usa-character-count__message" aria-live="polite">
      You can enter up to 25 characters
    </span>
  </div>
</form>

<form class="usa-form">
  <div class="usa-character-count">
    <div class="usa-form-group">
      <label class="usa-label" for="with-hint-textarea">
        Textarea
      </label>
      <span id="with-hint-textarea-hint" class="usa-hint">
        This is a textarea with a character counter.
      </span>
      <textarea class="usa-textarea usa-character-count__field" id="with-hint-textarea" maxlength="50" name="with-hint-textarea" rows="5" aria-describedby="with-hint-textarea-info with-hint-textarea-hint"></textarea>
    </div>

    <span id="with-hint-textarea-info" class="usa-hint usa-character-count__message" aria-live="polite">
      You can enter up to 50 characters
    </span>
  </div>
</form>

## Checkbox
<form class="usa-form">
  <fieldset class="usa-fieldset">
    <legend class="usa-legend">Select any historical figure</legend>
    <div class="usa-checkbox">
      <input class="usa-checkbox__input" id="check-historical-truth" type="checkbox" name="historical-figures" value="sojourner-truth" checked>
      <label class="usa-checkbox__label" for="check-historical-truth">Sojourner Truth</label>
    </div>
    <div class="usa-checkbox">
      <input class="usa-checkbox__input" id="check-historical-douglass" type="checkbox" name="historical-figures" value="frederick-douglass">
      <label class="usa-checkbox__label" for="check-historical-douglass">Frederick Douglass</label>
    </div>
    <div class="usa-checkbox">
      <input class="usa-checkbox__input" id="check-historical-washington" type="checkbox" name="historical-figures" value="booker-t-washington">
      <label class="usa-checkbox__label" for="check-historical-washington">Booker T. Washington</label>
    </div>
    <div class="usa-checkbox">
      <input class="usa-checkbox__input" id="check-historical-carver" type="checkbox" name="historical-figures"  value="george-washington-carver" disabled>
      <label class="usa-checkbox__label" for="check-historical-carver">George Washington Carver</label>
    </div>
  </fieldset>
</form>

## Combobox
<form class="usa-form">
<label class="usa-label" for="fruit">Select a fruit</label>
<div class="usa-combo-box">
  <select
    class="usa-select"
    name="fruit"
    id="fruit">
    <option value>Select a fruit</option>
    <option value="apple">Apple</option>
    <option value="apricot">Apricot</option>
    <option value="avocado">Avocado</option>
    <option value="banana">Banana</option>
    <option value="blackberry">Blackberry</option>
    <option value="blood orange">Blood orange</option>
    <option value="blueberry">Blueberry</option>
    <option value="boysenberry">Boysenberry</option>
    <option value="breadfruit">Breadfruit</option>
    <option value="buddhas hand citron">Buddha's hand citron</option>
    <option value="cantaloupe">Cantaloupe</option>
    <option value="clementine">Clementine</option>
    <option value="crab apple">Crab apple</option>
    <option value="currant">Currant</option>
    <option value="cherry">Cherry</option>
    <option value="custard apple">Custard apple</option>
    <option value="coconut">Coconut</option>
    <option value="cranberry">Cranberry</option>
    <option value="date">Date</option>
    <option value="dragonfruit">Dragonfruit</option>
    <option value="durian">Durian</option>
    <option value="elderberry">Elderberry</option>
    <option value="fig">Fig</option>
    <option value="gooseberry">Gooseberry</option>
    <option value="grape">Grape</option>
    <option value="grapefruit">Grapefruit</option>
    <option value="guava">Guava</option>
    <option value="honeydew melon">Honeydew melon</option>
    <option value="jackfruit">Jackfruit</option>
    <option value="kiwifruit">Kiwifruit</option>
    <option value="kumquat">Kumquat</option>
    <option value="lemon">Lemon</option>
    <option value="lime">Lime</option>
    <option value="lychee">Lychee</option>
    <option value="mandarine">Mandarine</option>
    <option value="mango">Mango</option>
    <option value="mangosteen">Mangosteen</option>
    <option value="marionberry">Marionberry</option>
    <option value="nectarine">Nectarine</option>
    <option value="orange">Orange</option>
    <option value="papaya">Papaya</option>
    <option value="passionfruit">Passionfruit</option>
    <option value="peach">Peach</option>
    <option value="pear">Pear</option>
    <option value="persimmon">Persimmon</option>
    <option value="plantain">Plantain</option>
    <option value="plum">Plum</option>
    <option value="pineapple">Pineapple</option>
    <option value="pluot">Pluot</option>
    <option value="pomegranate">Pomegranate</option>
    <option value="pomelo">Pomelo</option>
    <option value="quince">Quince</option>
    <option value="raspberry">Raspberry</option>
    <option value="rambutan">Rambutan</option>
    <option value="soursop">Soursop</option>
    <option value="starfruit">Starfruit</option>
    <option value="strawberry">Strawberry</option>
    <option value="tamarind">Tamarind</option>
    <option value="tangelo">Tangelo</option>
    <option value="tangerine">Tangerine</option>
    <option value="ugli fruit">Ugli fruit</option>
    <option value="watermelon">Watermelon</option>
    <option value="white currant">White currant</option>
    <option value="yuzu">Yuzu</option>
  </select>
</div>


  </form>

  ## Date input
  <form class="usa-form">
  <fieldset class="usa-fieldset">
    <legend class="usa-legend">Date of birth</legend>
    <span class="usa-hint" id="dobHint">For example: 4 28 1986</span>
    <div class="usa-memorable-date">
      <div class="usa-form-group usa-form-group--month">
        <label class="usa-label" for="date_of_birth_1">Month</label>
        <input class="usa-input usa-input--inline" aria-describedby="dobHint" id="date_of_birth_1" name="date_of_birth_1" type="text" maxlength="2" pattern="[0-9]*" inputmode="numeric" value="">
      </div>
      <div class="usa-form-group usa-form-group--day">
        <label class="usa-label" for="date_of_birth_2">Day</label>
        <input class="usa-input usa-input--inline" aria-describedby="dobHint" id="date_of_birth_2" name="date_of_birth_2" type="text" maxlength="2" pattern="[0-9]*" inputmode="numeric" value="">
      </div>
      <div class="usa-form-group usa-form-group--year">
        <label class="usa-label" for="date_of_birth_3">Year</label>
        <input class="usa-input usa-input--inline" aria-describedby="dobHint" id="date_of_birth_3" name="date_of_birth_3" type="text" minlength="4" maxlength="4" pattern="[0-9]*" inputmode="numeric" value="">
      </div>
    </div>
  </fieldset>
</form>

## Date picker
<form class="usa-form">
  <div class="usa-form-group">
    <label class="usa-label" id="appointment-date-label" for="appointment-date">Appointment date</label>
    <div class="usa-hint" id="appointment-date-hint">mm/dd/yyyy</div>
    <div class="usa-date-picker">
      <input 
        class="usa-input" 
        id="appointment-date" 
        name="appointment-date" 
        type="text" 
        aria-describedby="appointment-date-label appointment-date-hint">
    </div>
  </div>
</form>

## Date range picker
<form class="usa-form">
  <div class="usa-date-range-picker">
    <div class="usa-form-group">
      <label class="usa-label" id="event-date-start-label" for="event-date-start">Event start date</label>
      <div class="usa-hint" id="event-date-start-hint">mm/dd/yyyy</div>
      <div class="usa-date-picker">
        <input class="usa-input" id="event-date-start" name="event-date-start" type="text" aria-describedby="event-date-start-label event-date-start-hint">
      </div>
    </div>
    <div class="usa-form-group">
      <label class="usa-label" id="event-date-end-label" for="event-date-end">Event end date</label>
      <div class="usa-hint" id="event-date-end-hint">mm/dd/yyyy</div>
      <div class="usa-date-picker">
        <input class="usa-input" id="event-date-end" name="event-date-end" type="text" aria-describedby="event-date-end-label event-date-end-hint">
      </div>
    </div>
  </div>
</form>

## Dropdown
<form class="usa-form">
  <label class="usa-label" for="options">Dropdown label</label>
  <select class="usa-select" name="options" id="options">
    <option value>- Select -</option>
    <option value="value1">Option A</option>
    <option value="value2">Option B</option>
    <option value="value3">Option C</option>
  </select>
</form>

## File input
<!-- Start: @file-input--default -->
<div class="usa-form-group">
  <label class="usa-label" for="file-input-single">Input accepts a single file</label>
  <input id="file-input-single"
    class="usa-file-input"
    type="file"
    name="file-input-single"
    />
</div>
<!-- End: @file-input--default -->

<!-- Start: @file-input--specific -->
<div class="usa-form-group">
  <label class="usa-label" for="file-input-specific">Input accepts only specific file types</label>
  <span class="usa-hint" id="file-input-specific-hint">Select PDF or TXT files</span>
  <input id="file-input-specific"
    class="usa-file-input"
    type="file"
    name="file-input-specific"
    aria-describedby="file-input-specific-hint"accept=".pdf,.txt"/>
</div>
<!-- End: @file-input--specific -->

<!-- Start: @file-input--multiple -->
<div class="usa-form-group">
  <label class="usa-label" for="file-input-multiple">Input accepts multiple files</label>
  <span class="usa-hint" id="file-input-multiple-hint">Select one or more files</span>
  <input id="file-input-multiple"
    class="usa-file-input"
    type="file"
    name="file-input-multiple"
    aria-describedby="file-input-multiple-hint"multiple/>
</div>
<!-- End: @file-input--multiple -->

<!-- Start: @file-input--error -->
<div class="usa-form-group usa-form-group--error">
  <label class="usa-label usa-label--error" for="file-input-error">Input has an error</label>
  <span class="usa-hint" id="file-input-error-hint">Select any valid file</span>
  <span class="usa-error-message" id="file-input-error-alert" role="alert">Display a helpful error message</span>
  <input id="file-input-error"
    class="usa-file-input"
    type="file"
    name="file-input-error"
    aria-describedby="file-input-error-hint"/>
</div>
<!-- End: @file-input--error -->

<!-- Start: @file-input--disabled -->
<div class="usa-form-group">
  <label class="usa-label" for="file-input-disabled">Input in a disabled state</label>
  <input id="file-input-disabled"
    class="usa-file-input"
    type="file"
    name="file-input-disabled"
    disabled/>
</div>
<!-- End: @file-input--disabled -->

## Radio buttons
<form class="usa-form">
  <fieldset class="usa-fieldset">
    <legend class="usa-legend usa-legend">Select one historical figure</legend>
    <div class="usa-radio">
      <input class="usa-radio__input" id="historical-truth" type="radio" name="historical-figures" value="sojourner-truth">
      <label class="usa-radio__label" for="historical-truth">Sojourner Truth</label>
    </div>
    <div class="usa-radio">
      <input class="usa-radio__input" id="historical-douglass" type="radio" name="historical-figures" value="frederick-douglass">
      <label class="usa-radio__label" for="historical-douglass">Frederick Douglass</label>
    </div>
    <div class="usa-radio">
      <input class="usa-radio__input" id="historical-washington" type="radio" name="historical-figures" value="booker-t-washington">
      <label class="usa-radio__label" for="historical-washington">Booker T. Washington</label>
    </div>
    <div class="usa-radio">
      <input class="usa-radio__input" id="historical-carver" type="radio" name="historical-figures" value="george-washington-carver" disabled>
      <label class="usa-radio__label" for="historical-carver">George Washington Carver</label>
    </div>
  </fieldset>
</form>

## Range slider
<form class="usa-form">
  <label class="usa-label" for="range-slider">Range slider</label>
  <input id="range-slider" class="usa-range" type="range" min="0" max="100" step="10" value="20">
</form>

## Text input
<form class="usa-form">
  <label class="usa-label" for="input-type-text">Text input label</label>
  <input class="usa-input" id="input-type-text" name="input-type-text" type="text">

  <label class="usa-label" for="input-focus">Text input focused</label>
  <input class="usa-input usa-focus" id="input-focus" name="input-focus" type="text">

  <div class="usa-form-group usa-form-group--error">
    <label class="usa-label usa-label--error" for="input-error">Text input error</label>
    <span class="usa-error-message" id="input-error-message" role="alert">Helpful error message</span>
    <input class="usa-input usa-input--error" id="input-error" name="input-error" type="text" aria-describedby="input-error-message">
  </div>

  <label class="usa-label" for="input-success">Text input success</label>
  <input class="usa-input usa-input--success" id="input-success" name="input-success" type="text">

  <label class="usa-label" for="input-type-textarea">Text area label</label>
  <textarea class="usa-textarea" id="input-type-textarea" name="input-type-textarea"></textarea>
</form>

## Time picker
<form class="usa-form">
  <div class="usa-form-group">
    <label class="usa-label" id="appointment-time-label" for="appointment-time">Appointment time</label>
    <div class="usa-hint" id="appointment-time-hint">hh:mm</div>
    <div class="usa-time-picker">
      <input class="usa-input" id="appointment-time" name="appointment-time" type="text" aria-describedby="appointment-time-label appointment-time-hint">
    </div>
  </div>
</form>

## Validation
<form class="usa-form">
  <fieldset class="usa-fieldset">
    <legend class="usa-legend">Enter a code</legend>
    <div class="usa-alert usa-alert--info usa-alert--validation">
      <div class="usa-alert__body">
        <h3 class="usa-alert__heading">Code requirements</h3>
        <ul class="usa-checklist" id="validate-code">
          <li class="usa-checklist__item usa-checklist__item--checked" data-validator="uppercase">Use at least one uppercase character</li>
          <li class="usa-checklist__item" data-validator="numerical">Use at least one number</li>
        </ul>
      </div>
    </div>
    <label class="usa-label" for="code">Code</label>
    <input class="usa-input" id="code" name="code" type="text"
      aria-describedby="validate-code"
      data-validate-uppercase="[A-Z]"
      data-validate-numerical="\d"
      data-validation-element="#validate-code">
    <input class="usa-button" type="submit" value="Submit code">
  </fieldset>
</form>