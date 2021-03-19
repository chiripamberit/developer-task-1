### Developer Task 1 

* You will receive instructions from Cassava Smartech on what's required.

Solution 
Added key word static to private final because non-static variable LOGGER cannot be referenced from a static context
Changed @PreInsert to be @PrePersist  on SubscriberRequest.java line 42 
super key word is used to refer to the immediate parent class instance variable or methods commented out the line with code, "this(super);" PartnerCodeValidatorImpl line 18
•	Spring data jpa doesnt have a persist() it has save() and saveAndFlush(), Spring data jpa doesnt have a update() it uses save() to update entitiesThis for class EnquiriesServiceImpl line 36 and 39 and class CreditsServiceImpl,  line 36 and 39
•	@PathVariable("partnerCode") was missing for argument pCode EpayResource line 28
•	instance variables in EpayResource needed to be autowired to allow dependancy injection to occur
changed service to support soap 1.1
