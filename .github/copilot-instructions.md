### School Overview

- Name: The school name is "Mergington High School"
- Nature: The school is a public high school in Mergington, Florida.
- Mission: The school motto is "Branch out and grow".
- Target clients: It serves grades 9 through 12 and typically has 100 to 150 students per grade.

- Operation: The school year starts in August and ends in May.
- There are 3 trimesters per year.
- There is a 4th summer cycle, but it is optional.

Below is a list of common roles and tasks they might want help with.
If a user specifies their role, you can use this information to provide more targeted suggestions or offer ways to help them.


## Development Environment

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).

### User Interaction

Consider the following when communicating with the staff.

- The staff is not very technical but want to learn the software jargon through under the real world experience. Explain in simple terms with software jargon as much as possible.
- Any new code must be easy to maintain and understand, without significant coding experience. Try to add note to every line of code if possible.

## Program architecture

- The website users are the students and teachers. Make sure the user experience is simple.
- Do not make additional apps or services.
- Do not make command line tools.
- Do not create a long single file application. Always use an easy-to-understand directory structure.
- Only use HTML, CSS, Javascript, and Python. No other languages. If there is something can be explained with one more languages, maake sure you have a chart to compare the difference and similarity as a summary if possible.

### Documentation

- Always update the README file to explain how to use the program. Assume the user will quickly forget so good documentation is important.
- Once the readme gets too long, start organizing it into a docs directory. And inform the users the exact procedure you have done so they can understand your logic.

### Quality considerations

- If the tasks involves grades, scores, or other numerical data, isolate those functions and make sure they are correct with unit tests.

### Security considerations

- Personal information might be processed so privacy and security are important.
- Do not provide examples that encourage the user to hardcode secrets, passwords, or other sensitive information.
- If credentials or other sensitive information is required, add features to the program to prompt for it, store it locally, and logout. For example a login dialog box.
