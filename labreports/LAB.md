# Lab Report Template for CIS411_Lab0
Course: Messiah College CIS 411, Fall 2018<br/>
Instructors: [Joel Worrall](https://github.com/tangollama) & [Trevor Bunch](https://github.com/trevordbunch)<br/>
Name: Ben Underwood<br/>
GitHub: [benunderw](https://github.com/benunderw)<br/>

# Step 1: Fork this repository
- Forked repository URL: https://github.com/benunderw/cis411_lab0
- Diagram:
![Diagram](https://lh3.googleusercontent.com/hoo8O6Sd0agv12Ildmh1dNkBqZAbpMfrIytSgcm_foIMfwfzQZ1PVNGvY0SWJ1on_Ue9XRQreDXK0vI1q7WczrlUhv-RXFTRV1GIxk657arBF5Y_FnSBePZAT_9V5DTVv2R_DYbe8uYgywMXbPkhvRX4s-jam12kE0h2Rqy-Z28v6Q2ZECVCqG-C9pTYW8Kx0w150h5rgz58xJTvk_udU2bT0gk7oEXCrd3fi0dESwol49-W8gFZjmzr98m3faUTnkWOLG08Z9GbgBUGQmtAy3I3VLgjmO7-Aagl-Jk0-EA92v_4zznPCraZ1qOOstfs8LllnbRcMP2XWy-glyZWS0Mx_MSccbZqTxP6Z1aNCkoMwZCJg7gAipUrsr2TNWg7Fb6pKiDHQfRlZqVwjwt8R6tE74MKvDb5chKegKG_3-_lMWYWZ2V3BSeloGdF-rUirZ3ptgxhfh-3Gc9pHb0e7xe2Ba59KR8Yxq4qFbvy2P3LP_4jokZodgmnPvzT0JeDw6FVg2BSBMbFKQ3HCaVUEdrYCqmS18OBOhFHF2kFgZNw624WC1CtbMOJCuFzI8GEZ-fuf4_9xJBDKhRjV1PCKuPf8lvr3fy3iGE550XZPH3oLPT_Tnetq9p1V3C5ck3S=w930-h697-no)

# Step 2: Clone your forked repository from the command line
- My GraphQL response from adding myself as an account on the test project
```
{
  "data": {
    "mutateAccount": {
      "id": "2bffefb4-d688-43e3-8e29-3e4f9f4efaac",
      "name": "Benjamin Underwood",
      "email": "bu1157@messiah.edu"
    }
  }
}
```

# Step 3: Creating a feature branch
- The output of my git commit log
```
d2ddea5 (HEAD -> master, origin/master, origin/HEAD) Version 0.0.1 of the lab instructions
ab312fc more progress
62fb0a5 more progress
fe1937b more in the lab instructions
3e807fb first section
9ae6b83 remove LAB.md
e429c1a lab instructions
968099e remove test db
7362cd1 working
44ce6ae Initial commit
```
- The accompanying diagram of what my feature branch precisely and conceptually represents

# Step 4: Setup a Continuous Integration configuration
- What is the .circleci/config.yml doing?
- What do the various sections on the config file do?
- When a CI build is successful, what does that philosophically and practically/precisely indicate about the build?
- If you were to take the next step and ready this project for Continuous Delivery, what additional changes might you make in this configuration (conceptual, not code)?

# Step 5: Merging the feature branch
* The output of my git commit log
* A screenshot of the _Jobs_ list in CircleCI

# Step 6: Submitting a Pull Request
_Remember to reference at least one other student in the PR content via their GitHub handle._

# Step 7: [EXTRA CREDIT] Augment the core project
PR reference in the report to one of the following:
1. Add one or more unit tests to the core assignment project. 
2. Configure the CircleCI config.yml to automatically build a Docker image of the project.
3. Configure an automatic deployment of the successful CircleCI build to an Amazon EC2 instance.
