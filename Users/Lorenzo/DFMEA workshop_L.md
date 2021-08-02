- Why should we should we invest on FMEA? -> FMEA is an essential part of the journey towards  zero-defects 
- Answers the question: *"Did i specified the correct requirement?"*
![[Screenshot 2021-08-02 at 10.06.19.png]]

[[DFMEA]] process:
1. Customer defines functional requirements
2. Design Team defines product design to meet these requirements 
3. Design FMEA evaluates how the design may fail to produce product design

Example of typical system studied with DFMEA. 
![[Screenshot 2021-08-02 at 10.20.03.png]]

##### FMEA Steps
1. Potential causes and occurrence
	1. Functions and requirements
		- Clarify the item design intent or process purpose. This assists in the determination of the potential failure mode for each attribute or aspect of the function. If we don't have a good understanding of the item design intent we are likely going to have a weak design.
		-  [[DFMEA]] should be done ahead the design activities. 
		-  The outcome of this activity should be defined in technical terms avoiding statements like "this should have a good quality"
	2. Potential Failure Modes
		- The failure mode is defined as the way in which a product or process could fail to meet the design intent or process requirements. 
		> The assumption is made the failure could occur but may not necessarily occur. What does this mean in reality?  There are many things that may go wrong. Just because they have not gone wrong yet does not mean they may not go wrong in the future.
	 - For each functional requirement we have a failure mode. It works in tandem with the functions and requirements column. 
	4. Potential effects
		> The effects for each potential failure mode shall be identified and considered against subsequent manufacturing steps, higher level assemblies, the final product and the end customer.
	5. Severity Ranking
	![[Screenshot 2021-08-02 at 10.46.09.png]]
	
	6. Classification
	 - I should try to redesign the product to remove the more severe failure modes. However, not always is possible. 
	 - Classify severe failure modes as characteristics.
2. Potential causes and occurrence
	 1. Potential causes
		> The potential cause shall be identified for each potential failure mode. One potential failure mode may have several different causes, each of which should be listed in separate FMEA lines 
		> Its the cause of the failure mode not the cause of the effect. These may be very different

	2. Controls prevention
		- Prevention controls (Design/Process error proofing, design standards, equipment maintenance) are the recommended approach and have a high potential of reducing the occurrence of a failure. 
	3. Occurrence ranking
		![[Screenshot 2021-08-02 at 11.13.37.png]]
		
	1. Controls detection
		> Detection control may take place at the activity or operation where the failure occurred or at subsequent steps.
	
     5. Detection Ranking

		> The likelihood of detection of the failure shall be ranked using a 1 to 10 number scale.
	
		- This shall take into account detection controls in place within the design or production process.
		  ![[Screenshot 2021-08-02 at 11.15.33.png]]
		  
	- We should strive to detect failures **before or during** the design phase (this is emphasized in the table )
3. Risk and Recommended Actions
	1. RPN should be calculated for each identified risk
	2. Usually companies set a threshold and consider only failure modes above this. **This is now considered a bad practice**
		> It is good practice to review risks that have a high severity ranking first, followed by risks that have an occurrence or detection ranking of 9 or 10, regardless of the overall RPN in order to prevent escapes.
	3. Recommended actions:
	![[Screenshot 2021-08-02 at 11.26.58.png]]
###### Misc
- We cannot rely on processes controls to detect the weaknesses of the design.
- The actions taken by the suppliers have not direct impact on the calculations of detection. 
