## Winston v.0.01

Easily create and deploy assets across a variety of cloud platforms like [AWS](https://aws.amazon.com/), 
[GCP](https://cloud.google.com/), [Azure](https://azure.microsoft.com), [DO](https://www.digitalocean.com/),
[](https://console.scaleway.com), and [Vultr](https://my.vultr.com/).
	
### Application Components

- User Interface: HTML/CSS.
- Backend: [Ansible](https://www.ansible.com/), [Teraform](https://www.terraform.io/), and Bash.

### High-Level Application Flow

1. User goes to a website or loads an HTML file.
2. User picks a provider (AWS, GCP, Azure, DO).
3. User chooses a server type.
4. User selects an operating system.
5. User decides how much memory the server should have.
6. User chooses how much storage space they need.
7. User enters a server name.
8. User clicks the "deploy server" button.
9. System generates a Teraform script from user choices.
10. A Bash script then launches Teraform and executes the custom script.
11. Custom server(s) are built using the informations that was chosen in #02-07.
12. User is notified of a successful or unsuccessful build.
13. If successful, the user is presented with an IP address and login credentials.
14. If unsuccessful, an error message is displayed.

## Author
Created by [Patrick H. Mullins](http://www.pmullins.net). You can find me on  [Twitter](https://twitter.com/phmullins) and on [Telegram](https://telegram.org/) as @pmullins.

## License
Source is released under the MIT License (MIT) [license](license.md).

