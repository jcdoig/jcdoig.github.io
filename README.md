# Jean C. Doig

## How to setup github pages

Official Documentation [Link](https://pages.github.com/)
The official documentation describes how to create a page repository for a user, and how to get the main page setup.

### Customization

For Basic Customization use the settings GUI in the github repo. The GUI will create a _config.yml file in the repository with the theme information.

### Custom Domain

To use a custom domain use the settings GUI in the github repo. The GUI will create a CNAME file in the repository with the domain name. The change will happen immediatly, it might take up to 48h. You will need to provide the following information to your domain provider:

| Name            | Type  | TTL | Data             |
|-----------------|-------|-----|------------------|
| @               | A     | 1h  | 185.199.108.153  |
|                 |       |     | 185.199.109.153  |
|                 |       |     | 185.199.110.153  |
|                 |       |     | 185.199.111.153  |
| www             | CNAME | 1h  | jcdoig.github.io |

Once github verifies that your domain is pointing to their server they will allow you to check the use HTTPS checkbox.
