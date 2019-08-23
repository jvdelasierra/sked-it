Schedule: Time
		: Date
		: Table
		: Privacy Setting

User	: username
		: password
		: (Schedule)*
		: email
		: num_of_scheds
		: type
		: ID

Individual	: (User)
			: (Individual Profile)

Group		: (User)
			: (Individual)*
			: (Group Profile)
			: Group Settings

Organization: (User)
			: (Group)*
			: (Organization Profile)
			: (Organization)*
			: Organization Settings

