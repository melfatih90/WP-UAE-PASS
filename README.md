# UAE Pass Plugin

The UAE Pass Plugin integrates UAE Pass authentication into WordPress, allowing users to log in to their WordPress websites using UAE Pass credentials. UAE Pass is a secure and unified digital identity solution provided by the United Arab Emirates government.

## Features

- Seamless integration of UAE Pass authentication into WordPress login system.
- Customizable settings to configure UAE Pass authentication parameters.
- Support for both Arabic and English languages.
- Easy setup and configuration through the WordPress admin interface.

## Installation

1. Download the plugin zip file from the [GitHub repository](#) or install it directly from the WordPress plugin directory.
2. Upload the plugin files to the `/wp-content/plugins/uae-pass` directory, or install the plugin through the WordPress plugins screen directly.
3. Activate the plugin through the 'Plugins' screen in WordPress.
4. Configure the plugin settings by navigating to the UAE Pass settings page in the WordPress admin panel.
5. Enable the UAE Pass login button on the login form by activating the corresponding option in the plugin settings.

## Usage

1. After activating the plugin and configuring the settings, users will see the UAE Pass login button on the WordPress login form.
2. Clicking on the UAE Pass login button will redirect users to the UAE Pass authentication page, where they can log in using their UAE Pass credentials.
3. Upon successful authentication, users will be redirected back to the WordPress site and logged in automatically.

## Configuration

- **Client ID**: Enter the client ID provided by UAE Pass.
- **Scope**: Define the scope of access required for authentication.
- **Callback URL**: Specify the URL to which users should be redirected after authentication.
- **Login Button**: Select the image for the UAE Pass login button.
- **API Environment**: Choose the API environment (production or staging) for authentication.


## SandBox Configuration
- **Client ID**: sandbox_stage.
- **Secret**: c2FuZGJveF9zdGFnZTpzYW5kYm94X3N0YWdl.
- **Scope**: urn:uae:digitalid:profile:general&acr_values=urn:safelayer:tws:policies:authentication:level:low
- **Callback URL**:  uae-auth-callback.
- **Login Button**: Select the image for the UAE Pass login button.
- **API Environment**: Choose the API environment (staging).


## Frequently Asked Questions

### How do I obtain a UAE Pass client ID?
To obtain a client ID for UAE Pass authentication, you need to register your application with UAE Pass. Visit the UAE Pass developer portal for more information and to request access.

### Can I customize the appearance of the UAE Pass login button?
Yes, you can customize the appearance of the UAE Pass login button by selecting a different image from the plugin settings.

### Is UAE Pass authentication secure?
Yes, UAE Pass authentication is a secure digital identity solution provided by the United Arab Emirates government, ensuring a high level of security for user authentication.

## Support

For support or assistance with the UAE Pass Plugin, please [open an issue](#) on GitHub or contact us via [email](mailto:melfatih@scripto-tech.com).

## License

The UAE Pass Plugin is licensed under the [GNU General Public License v2.0](https://www.gnu.org/licenses/gpl-2.0.html) or later.
