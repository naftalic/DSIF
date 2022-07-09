html:
  Hello world! <br>
  This is the current date and time, as computed by Python:
  <py-script>
  from datetime import datetime
  now = datetime.now()
  now.strftime("%m/%d/%Y, %H:%M:%S")
  </py-script>
