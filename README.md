# Life-cycle-2.

A repo about React life components.

The two life cycles that affect the component in the DOM.

1.The componentDidMount() method (this method is called when a component is mounted/placed on the DOM.)

It is called once in the component life cycle and it signals that the component and all its sub-components have rendered properly. This is the best place to make API calls since, at this point, the component has been mounted and is available to the DOM.When one wants to fetch data or make an Ajax request.It is usually done inside this method.

2.The componentDidUpdate () method.

componentDidUpdate() is called after componentDidMount() and can be useful to perform some action when the state changes. componentDidUpdate() takes as its first two arguments the previous props and the previous state.It is invoked everytime the component updates

Note that the component is unmounted when it is no longer shownn in the view.
