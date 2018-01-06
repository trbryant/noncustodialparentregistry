# noncustodialparentregistry
Non-Custodial Parent Registry

#Initial Data Definition 
#Based on a discussion regarding non-custodial paternity rights on Facebook we wanted to develop the facility for a national registry.  
#This project will focus on capturing / storing all pertinent data that is required to centralize and streamline a national database.

DRAFT v1.0

{
	"registrant_id":"abcdef12345",
	"dob":"01/01/1980",
	"gender":"M",
	"spouse_first":"Vanessa",
	"ssn":123456789,
	"primary_phone":4045551212,
	"secondary_phone":7705551212,
	"primary_emai":"involved_dad@gmail.com",
	"secondary_email":"concerned_dad@gmail.com",
	"names":	
				{"first":"Babatunde",
				 "middle":"M",
				 "last":"Owelu",
				 "number":0,
				 "recorddate":"1/5/2018"
				},
				{"first":"Eric",
				 "middle":"M",
				 "last":"Johnson",
				 "number":0,
				 "recorddate":"12/14/1998"
				},
	"address":
				{
				"street_addr":"123 Main Street",
				"street_number":123,
				"street_name":"Main Street",
				"city":"Anytown",
				"state":"MA",
				"zip_code":12345,
				"zipplus4":123451234,
				"address_date":"1/5/2018},
				"number":0
				},
				{
				"street_addr":"456 Water Street",
				"street_number":456,
				"street_name":"Water Street",
				"city":"Anytown",
				"state":"MA",
				"zip_code":12346,
				"zipplus4":123461235,
				"address_date":"12/14/1998
				"number":1
				},
	"partner_detail":
				{
					"partner_id":987654321
					"partner_first":"Serena",
					"partner_middle":"E",
					"partner_last":"Williams",
					"partner_dob":"7/14/1984",
					"partner_gender":"F",
					"partner_ssn":654321987
					"street_addr":"123 Main Street",
					"street_number":123,
					"street_name":"Main Street",
					"city":"Anytown",
					"state":"MA",
					"zip_code":12345,
					"zipplus4":123451234,
					"address_date":"1/5/2018},
				},
				{
					"partner_id":987654123
					"partner_first":"Venus",
					"partner_middle":"E",
					"partner_last":"Jones",
					"partner_dob":"7/14/1982",
					"partner_gender":"F",
					"partner_ssn":654321789
					"street_addr":"456 Water Street",
					"street_number":456,
					"street_name":"Water Street",
					"city":"Anytown",
					"state":"MA",
					"zip_code":12346,
					"zipplus4":123461235,
					"address_date":"12/14/1998
				},
	"relation_details":
				{
					"paternity_id":512874329,
					"partner_id":987654123,
					"partner_first":"Venus",
					"state_of_conception":"MA",
					"ssn":481957934,
					"child_dob":"01/04/2018",
					"child_gender":"M",
					"child_first":"James",
					"child_middle":"Earl",
					"child_last":"Jones",
					"child_birth_city":"Anytown",
					"child_birth_state":"MA",
					"child_birth_zip":"12345"
					"relation_type":"Father"
				},
				{
					"paternity_id":512874329,
					"partner_id":987654321,
					"partner_first":"Serena",
					"state_of_conception":"MA",
					"ssn":481957934,
					"child_dob":"01/04/2018",
					"child_gender":"M",
					"child_first":"Richard",
					"child_middle":"Earl",
					"child_last":"Williams",
					"child_birth_city":"Anytown",
					"child_birth_state":"MA",
					"child_birth_zip":"12345"
					"relation_type":"Father"
				}	
	
}
