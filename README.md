# College Help Desk

A web portal that puts everyday college information and student services in one place, with an AI assistant to answer common questions.

Instead of walking between the library, accounts office and admin block to find out something simple, students can look it up here.

## What it does

**Anyone (no login)**
- College info, vision and FAQs

**Registered students**
- Ask the AI assistant about college services, locations, library and faculty
- Check if a book is available in the library
- Look up faculty details and the holiday list
- Find academic blocks, hostels and other campus locations
- Check fee deposit status (view only, no payments)
- Submit queries to the college
- Upload assignments and receive teacher feedback

**Teachers**
- View submitted assignments and write feedback

## How it flows

- **Student:** Register → Log in → Use services
- **Assignments:** Student submits → Teacher reviews → Feedback shown to student

## Tech stack

| Part | Used |
|------|------|
| Frontend | HTML, CSS, JavaScript |
| Backend |Python (Flask)|
| Database | MySQL |
| AI model / API | Google Gemini API |
| Auth | Session-based login |

## Getting started

```bash
git clone <https://github.com/Abhi5hekkumar/AI-powered-student-college-help-desk-.git>
cd <cd AI-powered-student-college-help-desk--main>
# install dependencies
# add your keys to a .env file (see .env.example)
# run the project
```

Replace the steps above with the actual commands for your project.

## Screenshots


## Notes on security

- Keep API keys and passwords out of the repo (use `.env`, and add it to `.gitignore`)
- Only teachers should be able to review assignments
- A student should never see another student's records
- Use dummy data in demos

## Planned improvements

- Multilingual assistant
- Interactive campus map
- Assignment deadline reminders and feedback notifications
- Query status tracking
- Library book reservation

## Contributing

Fork the repo, create a branch, make your changes and open a pull request.

## License

Not declared yet. Add a `LICENSE` file ( MIT) before sharing publicly.

## Author

Abhishek Kumar
