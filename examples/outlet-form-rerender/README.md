# Welcome to Remix

- [Remix Docs](https://remix.run/docs)

In this example, we will be looking at how to update a Form with uncontrolled fields with the updated values when the form does not unmount between transitions.

For example, when the form is rendered inside a nested route, changing the route from the parent route does not cause the form to unmount but updates the values of the fields.

Here we have a simple example where we list a set of users and, clicking on the users will open a form inside a nested route. You can check the explanation at [$userId.tsx](app/routes/users/$userId.tsx)
