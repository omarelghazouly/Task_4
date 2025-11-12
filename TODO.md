# TODO: Implement Missing Tests

## Backend Test Implementation
- [ ] Implement login test in `server/tests/auth.test.js`
  - Make POST request to `/auth/login` with registered user credentials
  - Assert 200 status, presence of JWT token, and matching user profile
  - Store the new token for subsequent tests

## Frontend Test Implementation
- [ ] Implement merchant filtering test in `client/tests/allPerksPage.test.jsx`
  - Render AllPerks component with seeded perk
  - Select the seeded perk's merchant from dropdown
  - Wait for perks to load and verify seeded perk is displayed
  - Check summary text shows correct number of matching perks

## Verification
- [ ] Run backend tests: `cd server && npm run test`
- [ ] Run frontend tests: `cd client && npm run test`
- [ ] Ensure all tests pass
