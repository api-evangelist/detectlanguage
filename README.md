# DetectLanguage

DetectLanguage is a language detection REST API that analyzes text samples and returns the identified language along with a confidence score. Supporting 216 languages, the API enables developers to identify languages from brief phrases to full documents, with batch processing support for multiple texts in a single request.

## Resources

- [Website](https://detectlanguage.com)
- [Documentation](https://detectlanguage.com/documentation/v3)
- [Pricing / Plans](https://detectlanguage.com/plans)
- [GitHub Organization](https://github.com/detectlanguage)
- [Sign Up](https://detectlanguage.com/users/sign_up)
- [Contact](https://detectlanguage.com/contact)
- [Terms of Service](https://detectlanguage.com/terms)
- [Privacy Policy](https://detectlanguage.com/privacy_policy)

## API

Base URL: `https://ws.detectlanguage.com/v3`

Authentication: Bearer token — `Authorization: Bearer <your-api-key>`

Key endpoints:

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /v3/detect | Detect language of a single text |
| POST | /v3/detect-batch | Detect languages for multiple texts |
| GET | /v3/account/status | Check current usage and limits |
| GET | /v3/languages | List all supported languages |

## SDKs

Official client libraries are available for Ruby, Python, Node.js, Go, Java, PHP, and .NET via the [detectlanguage GitHub organization](https://github.com/detectlanguage).

## Plans

| Plan | Price | Requests/Day | Data/Day |
|------|-------|--------------|----------|
| Free | $0/mo | 1,000 | 1 MB |
| Basic | $5/mo | 100,000 | 20 MB |
| Plus | $15/mo | 1,000,000 | 200 MB |
| Premium | $40/mo | 10,000,000 | 2 GB |
| Premium 40M | $100/mo | 40,000,000 | 8 GB |
| Premium 100M | $200/mo | 100,000,000 | 20 GB |
| Custom | Contact | Custom | Custom |
