# myfitnesspal-alexa-skill-docker

### Deployment

Create a `.env` file with the following in order to automatically get your custom domain with SSL certificate via Let's Encrypt:

| Property            | Description                                 | Info/Default value                       |
|---------------------|---------------------------------------------|------------------------------------------|
| `VIRTUAL_HOST`      | Custom domain to use                        | *Optional*                               |
| `LETSENCRYPT_HOST`  | Custom domain to use                        | *Optional*                               |
| `LETSENCRYPT_EMAIL` | Email to generate SSL certificate           | *Optional*                               |