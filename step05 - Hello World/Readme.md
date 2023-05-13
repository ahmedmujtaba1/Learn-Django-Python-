
<p> Let’s write the first view. Open the file polls/views.py and put the following Python code in it: </p>
<h3> from django.http import HttpResponse


def index(request):
    return HttpResponse("Hello, world. You're at the polls index.")
  </h3>
