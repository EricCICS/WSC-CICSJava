<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Washington Systems Center(WSC) z/OS Connect workshop. 

Click [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/ZCINTRO%20-%20Introduction%20to%20zOS%20Connect%20EE.pdf){:target="_blank"} if you would like to download the z/OS Connect Introduction presentation.



## Accessing the hands-on lab

1) Click [here](Remote Desktop Windows.pdf){:target="_blank"} for detailed instruction on how to access the IBM virtual image that hosts the exercises.  You'll need to supply your credentials which are obtained by providing your email below on this page.

2) Download the Open API 2.0 API Provider lab booklets from the folder located [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/OpenAPI2){:target="_blank"} 

3) Download the Open API 2.0 API Requester lab booklets from the folder located [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/APIRequesters){:target="_blank"} 

4) Download the Open API 3.0 lab booklets from the folder loactated [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/OpenAPI3){:target="_blank"} 



## Remote Sytem Credentials

**Please enter your email address used for registration to retrieve your unique log in details.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">@</span>
<input type="email" class="form-control" placeholder="Registration Email" aria-label="Email" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
<em>Note you will need a confirmed registration to access the lab.</em>
</div>

## Help 
Having trouble with labs? Send an email to [Eric Higgins](mailto: erichiggins@us.ibm.com), and I will help you sort it out.
