# boilerplate
[![Deploy](http://tekos.co/wp-content/uploads/2019/11/deploy-to-tekos-e1575129615495.png)](https://chat.tekos.co/?msg=deploy%20template%20https://github.com/tekos-flow/sample%20#/user/@tekos-test:m.tekos.co)



Package.json

Use This format:

    "env": {
        "HOMESERVER": {
            "description": "Your Homeserver",
            "generator": "secret"
        },
        "WEB_CONCURRENCY": {
            "description": "The number of processes to run.",
            "value": "5"
        },
        "STRIPE_KEY": {
            "description": "Stripe key.",
            "required": "false"
        }
    }
