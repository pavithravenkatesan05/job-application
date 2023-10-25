# job-application<html>
<body>
  <div class="col-md-6 offset-md-3 mt-5">
    <a target="_blank" href="https://getform.io?ref=codepenHTML">
      <img alt="Getform.io Logo" src="https://i.imgur.com/Z2Nyxsm.png">
    </a>
    <br>
    <a target="_blank" href="https://getform.io?ref=codepenHTML" class="mt-3 d-flex">Getform.io | Get your free endpoint now</a>
    <h1>Simple Job Application Form</h1>
    <form accept-charset="UTF-8" action="https://getform.io/f/{your-form-endpoint-goes-here}" method="POST" enctype="multipart/form-data" target="_blank">
      <div class="form-group">
        <label for="exampleInputName">Full Name</label>
        <input type="text" name="fullname" class="form-control" id="exampleInputName" placeholder="Enter your name and surname" required="required">
      </div>
      <div class="form-group">
        <label for="exampleInputEmail1" required="required">Email address</label>
        <input type="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter your email address">
      </div>
      <div class="form-group">
        <label for="inputAddress">Address</label>
        <input type="text" name="address" class="form-control" id="inputAddress" placeholder="1234 Main St">
      </div>
      <div class="form-row">
        <div class="form-group col-md-6">
          <label for="inputCity">City</label>
          <input type="text" name="city" class="form-control" id="inputCity" placeholder="Istanbul">
        </div>
        <div class="form-group col-md-2">
          <label for="inputZip">Zip</label>
          <input type="text" name="zip" class="form-control" id="inputZip" placeholder="34000">
        </div>
      </div>
      <div class="form-group">
        <label for="example-tel-input" class="col-2 col-form-label">Telephone</label>
        <div class="col-10">
          <input class="form-control" name="tel" type="tel" value="1-(555)-555-5555" id="example-tel-input">
        </div>
      </div>
      <div class="form-group">
        <label for="example-date-input" class="col-3 col-form-label">Start Date</label>
        <div class="col-10">
          <input class="form-control" name="starting_date" type="date" value="2020-02-01" id="example-date-input">
        </div>
      </div>
      <div class="form-group mt-3">
        <label class="mr-4">Upload your CV:</label>
        <input type="file" name="file">
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
</body>

</html>
