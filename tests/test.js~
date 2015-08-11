
module.exports = {


  'step one' : function (browser) {
    browser
      .url('http://172.27.59.103:8087/EmployeeApplication')
      .waitForElementVisible('body', 1000)
     .click('a[id=AddEmployeeLink]')
	  // .waitForElementVisible('a[id=AddEmployeeLink]', 1000)
	   
	},
	
	 'step two' : function (browser) {
      browser
	   .url('http://172.27.59.103:8087/EmployeeApplication/jsp/add.jsp')
	   .waitForElementVisible('body', 1000)
      .setValue('input[name=code]', '101')
	  .setValue('input[name=name]', 'prati')
	  .setValue('input[name=city]', 'pune')
      .waitForElementVisible('button[id=SubmitEmployee]', 1000)
      .click('button[id=SubmitEmployee]')
      .pause(1000)
      //.assert.containsText('#code', '4000')


 

  },
  
  'step three' : function (browser) {
      browser
	   .url('http://172.27.59.103:8087/EmployeeApplication/list')
	   .waitForElementVisible('body', 1000)
    .end();
	}
};
