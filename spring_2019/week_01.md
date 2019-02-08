## Last Week's Accomplishments

This past week, I discussed the future plan for YACS Admin with our team lead Ada. We decided to get rid of YACS Admin as a separate project, since it hasn't really had any active development for a semester. Also, YACS API has been updated so that it can handle essentially all of what YACS Admin was designed to do, i.e. delete, update, add various courses. It would be much simpler to just use YACS API for these operations instead of an additional admin program. YACS Admin didn't actually add that much functionality, and was mostly utilizing the API itself. The YACS Admin UI could be reused, however, and I have been copying the basic frontend over to YACS web. This way, users can directly modify data directly in YACS. 

## This Week's Plan

This week I plan on implementing a basic edit button for courses in the feature/admin branch. This will link to a detail view of courses with input fields allowing a user to edit course data and save their changes. I think this will be pretty simple to implement as the detail view can be directly taken from YACS Admin. 

## Anything Blocking?

I was having some trouble using Docker and actually running YACS. Previously, with YACS Admin, I only had to use Angular. I got everything working eventually with some help, though, so I don't think it should be a blocker in the future.

## Notes

None
