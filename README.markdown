# Spike on websocketd and HTML Progress

based on [websocketd](http://websocketd.com/) and [HTML5 Has Built-In Progress Bars and Meters](https://www.256kilobytes.com/content/show/4399/get-these-dependencies-off-my-lawn-5-tasks-you-didnt-know-could-be-done-with-pure-html-and-css#html5-has-built-in-progress-bars-and-meters).

# Development

* `brew install websocketd`
* Run and re-run when the HTML changed:

  ```console
  $ rerun --no-notify -- \
      websocketd \
        --port=8080 \
        --staticdir public_html \
        --devconsole \
      ./count-to-11
  ```
