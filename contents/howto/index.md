---
template: page.pug
menu: Support
title: Support
---

<div class="alert alert-info" role="alert">
<div class="icon-left"><i class="glyphicon glyphicon-question-sign hugeicon"></i> </div>
<h4>Where to start?</h4>

Look at the [Frequently Asked Questions](faq.html) for a list of most frequently asked questions.
</div>

# Tutorials and guides

These tutorials cover various topics on how to use VOT toolkit in your experiments:

- [Tutorial for the Python version](tutorial_python.html)
- [Building tracker examples on Windows using Visual Studio](visualstudio.html)
- [Building tracker examples using CMake](cmake.html)
- [Setting up the workspace (Matlab)](workspace.html)
- [Integrate a tracker (Matlab)](integration.html)
- [Perform evaluation and submit results (Matlab)](perfeval.html)
- [Analyzing results and generating reports (Matlab)](analysis.html)
- [Reproducing the 2016 TPAMI paper results](analysis_vot2014.html)


# Documentation

- [Toolkit documentation (Matlab version)](http://docs.votchallenge.net/)
- [TraX protocol documentation](http://trax.readthedocs.io/)

# Support forum

If you did not find the information that you were looking for in the FAQ, documentation, or tutorials, you can <a href="https://groups.google.com/forum/?hl=en#!forum/votchallenge-help"> contact us on the support forum</a>.

<iframe id="forum_embed" src="javascript:void(0)" scrolling="no" frameborder="0" height="600">
</iframe>
<script type="text/javascript">
var a = document.getElementById("forum_embed");
var uri = encodeURIComponent(window.location.href);
a.src = "https:" + "//groups.google.com/forum/embed/?place=forum/votchallenge-help\u0026parenturl=" + uri;
function resize_handle() {
var a = $("#forum_embed");
a.attr('width', a.parent().width() + 'px');
}
$(window).resize(resize_handle);
resize_handle();
</script>

