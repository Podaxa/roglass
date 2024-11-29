|| !! USE STYLUS / STYLISH EXSTENTION FOR THIS !! ||

EDITABLE STUFF LISTED IN README

/* ==UserStyle==
@name           roglass
@namespace      github.com/openstyles/stylus
@version        1.0.0
@description    adds a glass like effect to roblox
==/UserStyle== */
@-moz-document domain("roblox.com")
{
    .dark-theme .content
    {
        background: rgba(255, 255, 255, 0); /* Semi-transparent white */
        backdrop-filter: blur(10px); /* Adds blur effect */
        -webkit-backdrop-filter: blur(10px); /* Safari support */
        border: 1px solid rgba(255, 255, 255, .1); /* Subtle border for aesthetics */
        border-radius: 10px; /* Rounded corners */
        padding: 15px; /* Adds some spacing inside */
    }

    /* Ensure text within the container is readable */
    .container-main *
    {
        color: #fff !important; /* Adjust text color for readability */
    }
}

@-moz-document domain("roblox.com")
{
    /* Glass effect for the navbar */
    .dark-theme .rbx-header
    {
        background: rgba(255, 255, 255, 0); /* Semi-transparent black */
        backdrop-filter: blur(10px); /* Adds blur effect */
        -webkit-backdrop-filter: blur(10px); /* Safari support */
        border: 1px solid rgba(255, 255, 255, 0.1); /* Subtle border for contrast */
        border-radius: 8px; /* Optional rounded corners */
    }

    /* Glass effect for the simple bar */
    .dark-theme .rbx-left-col
    {
        background: rgba(255, 255, 255, 0); /* Semi-transparent black */
        backdrop-filter: blur(10px); /* Adds blur effect */
        -webkit-backdrop-filter: blur(10px); /* Safari support */
        border: 1px solid rgba(255, 255, 255, .1); /* Subtle border for contrast */
        border-radius: 8px; /* Optional rounded corners */
    }

    /* Ensure text is readable on dark theme */
    .navbar-dark-theme a,
    .simple-bar-dark-theme a,
    .navbar-dark-theme .nav-item,
    .simple-bar-dark-theme .nav-item
    {
        color: #fff !important; /* White text for readability */
    }
}
@-moz-document domain("roblox.com") {
  /* Add shadow behind the navbar */
   .dark-theme .rbx-header {
    box-shadow: 0px 4px 7px rgba(0, 0, 0, 0.8); 
  }

  /* Add shadow behind the simple bar */
  .simple-bar-dark-theme {
    box-shadow: 0px 4px 7px rgba(0, 0, 0, 0.8);
  }
   .dark-theme .content  {
    box-shadow: 0px 10px 8px rgba(0, 0, 0, 0.8);
    }}
