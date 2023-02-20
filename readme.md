# Whatsapp API Tutorial


### How to use?

- Clone or download this repo
- Enter to the project directory
- Run `npm install`
- Run `npm run start:dev`
- Open browser and go to address `http://localhost:8000`
- Scan the QR Code
- Enjoy!

### Send message to group with attached image and caption [Modified by me]

**Existing Feature:**

- `name` : group name
- `message`: the message

Here the endpoint: `/send-group-message`

**New Feature: Sent Group Message with media and caption**
Endpoint: `/send-group-message`
Parameters: 'name' : group name, 'caption': the message, 'file': URL/location of the file
method: POST
body: raw JSON
{
    "name": "Group Name",
    "caption": "Message",
    "file": "https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png"
}

**New Feature: Docker**
- Run `docker compose up`






