# Portfolio Contact Backend

This backend receives form submissions from your portfolio's contact form and sends them to your email.

## Technologies
- Node.js
- Express
- Nodemailer
- dotenv

## API Endpoint

### POST `/api/contact`

**Request Body:**
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "subject": "Interested in your work",
  "phone": "1234567890",
  "message": "Hi, I love your work!"
}
