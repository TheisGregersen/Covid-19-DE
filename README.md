# Newest covid-19 updates on Germany.

### Get a quick and easy overview of Germanys situation and se how the virus has spread out since the first outbreak were registered on Januray 28, 2020 in the state of Bavaria. 
The graphs and visualisations presented in this report are based on data obtained from this [site](https://www.kaggle.com/headsortails/covid19-tracking-germany?fbclid=IwAR2ouNxb53Z-Mk4emTUpdZog9Uhm02krlCW0yC4woPArAbeF2lt5HyraS-4#covid_de.csv).


<h3 align="center">
Total
</h3>
<p align="center">
  <img width="700" src="BAN1.png">
</p>
<h3 align="center">
Per one milion inhabitant
</h3>
<p align="center">
  <img width="700" src="BAN2.png">
</p>

<h3 align="center">
Development of total cases, deaths and recoveries
</h3>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/overview_cum.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/Overview_byday.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

## Test af Victor
![gif](animation.gif)


## Slut test Victor

<h3 align="center">
Total infected Heatmap 
</h3>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/heatmap_DE.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

<h3 align="center">
Registered infected over weeks
</h3>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/heatmap_time.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>

<h3 align="center">
See if your country is fucked
</h3>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/test1234.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>



<details open>
<summary>Dropdown menu - Klik Her?</summary>
<br>
</h3>
<iframe src="https://theisgregersen.github.io/Covid-19-DE/test1234.html" sandbox="allow-same-origin allow-scripts" width="100%" height="500" scrolling="no" seamless="seamless" frameborder="0"> </iframe>
</details>



$("#seeAnotherField").change(function() {
  if ($(this).val() == "yes") {
    $('#otherFieldDiv').show();
    $('#otherField').attr('required', '');
    $('#otherField').attr('data-error', 'This field is required.');
  } else {
    $('#otherFieldDiv').hide();
    $('#otherField').removeAttr('required');
    $('#otherField').removeAttr('data-error');
  }
});
$("#seeAnotherField").trigger("change");

$("#seeAnotherFieldGroup").change(function() {
  if ($(this).val() == "yes") {
    $('#otherFieldGroupDiv').show();
    $('#otherField1').attr('required', '');
    $('#otherField1').attr('data-error', 'This field is required.');
    $('#otherField2').attr('required', '');
    $('#otherField2').attr('data-error', 'This field is required.');
  } else {
    $('#otherFieldGroupDiv').hide();
    $('#otherField1').removeAttr('required');
    $('#otherField1').removeAttr('data-error');
    $('#otherField2').removeAttr('required');
    $('#otherField2').removeAttr('data-error');
  }
});
$("#seeAnotherFieldGroup").trigger("change");


 <div class="form-group">
    <label for="seeAnotherFieldGroup">Do You Want To See Another Group of Fields?</label>
    <select class="form-control" id="seeAnotherFieldGroup">
          <option value="no">Not Particularly.</option>
          <option value="yes">I Guess!</option>
    </select>
  </div>
  
  <div class="form-group" id="otherFieldGroupDiv">
    <div class="row">
      <div class="col-6">
        <label for="otherField1">Group: Heres One!</label>
        <input type="text" class="form-control w-100" id="otherField1">
      </div>
      <div class="col-6">
        <label for="otherField2">Group: Another One!</label>
        <input type="text" class="form-control w-100" id="otherField2">
      </div>
    </div>
  </div>
  
  <div class="form-group">
    <label for="comments">Comments/Questions</label>
    <textarea class="form-control" id="comments" rows="3"></textarea>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>


