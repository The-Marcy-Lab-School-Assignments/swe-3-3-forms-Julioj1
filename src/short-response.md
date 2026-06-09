# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:** Accessibility is the practice of designing websites so that people of all abilities, including those with visual, auditory, motor, or cognitive disabilities, can use them effectively. It matters because it promotes inclusion, improves usability for everyone, and ensures equal access to information and services.

Labels make form inputs more accessible by clearly describing what information the user is expected to enter, reducing confusion. They also allow screen readers to properly announce input fields and let users click on the label to focus the input, which helps users with motor impairments.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:** The id attribute uniquely identifies an element on the page and is used to connect a <label> to an input using the label’s for attribute. The for attribute tells the browser which input the label is describing, improving accessibility and usability. The name attribute is used when submitting a form, because it defines the key under which the input’s value is sent to the server.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:** We use specific input types like email and number because they provide built-in validation and better user experience. For example, type="email" can check for a valid email format, and type="number" restricts input to numeric values. These input types also trigger more appropriate keyboards on mobile devices, making forms easier and faster to use.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:** A real example of form submission is a login form on a website like Gmail. When a user submits the form, the data (such as their email and password) is sent to the server, which checks the information against stored user records. If the credentials are valid, the server authenticates the user and grants access to their account. If not, the server returns an error message and denies access.
