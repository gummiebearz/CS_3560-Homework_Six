# Assumptions

- The Website checks facility availability, records outcomes, and saves the booking. The Renter is only charged after School Staff approves the request. Payment Service reports payment as either success or failure to Website. Email Service sends confirmation, failure, or rejection email triggered by Website.

- Payment Service internals are not modeled 


- **Activity Diagram**: The Renter can choose different date or quit, so I added a fourth endpoint

- **Sequence Diagram**: Includes a retry loop for Renter. School Staff respond to Website with approval or rejection