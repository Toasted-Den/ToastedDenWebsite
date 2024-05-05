# Toasted Den's Website

This is the official repository for the [Toasted Den website](https://toastedden.com). The website provides contact information for Toasted Den, including business inquiries and direct contact details.

## Setup

To view the website locally:

1. Clone this repository to your local machine using `git clone https://github.com/Toasted-Den/ToastedDenWebsite.git`
2. Navigate to the project directory using `cd`.
3. Open the `index.html` file in your web browser.

To run the website with Docker Compose:

1. Install Docker and Docker Compose with `sudo apt install docker.io docker-compose`.
2. Clone this repository to your local machine using `git clone https://github.com/Toasted-Den/ToastedDenWebsite.git`
3. Navigate to the project directory using `cd`.
4. Run `sudo docker-compose up -d` to start the container. You can now navigate to [localhost:8095](http://localhost:8095) to view the site.

Remember to add a firewall rule for the ports you will be using to host the site. In my case I use ports `80` and `8095`. Add your firewall rule(s) by running `sudo ufw allow 80`, `sudo ufw allow 8095`, and `sudo ufw enable` in the terminal on Debian based operating systems.

Ensure the firewall is active and allowing the ports through by running `sudo ufw status` in the terminal.

## Special Events
On occasion, the website will have a minor update for special events. You can view all previous special event versions of the site by navigating to the `./SpecialEvents` directory.

## Committing
I don't think there's much to improve on, but if you think you can enhance/ optimize the site; feel free to make a pull request!

## License

This project is licensed under the [CC0-1.0 License](LICENSE) - see the [LICENSE](LICENSE) file for details.
