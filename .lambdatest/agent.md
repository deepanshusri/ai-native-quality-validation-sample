# KaneAI Agent Instructions

## About the app
An Airbnb-style vacation rental demo (React + Vite) deployed to GitHub Pages with a mock API.
Main journeys: browse listings on the home page, search by destination/dates/guests,
open a listing detail page, pick check-in/check-out dates, review the price breakdown,
reserve, and view bookings. Login is optional for browsing.

## Test URL
Each PR is deployed to `https://deepanshusri.github.io/ai-native-quality-validation-sample/pr-<number>/`.
Main is deployed to the root of that site.

## Demo login
Email: lambdatestadmin@email.com
Password: password123

## Priorities
1. Anything that touches pricing: nightly price x nights, service fee (14%), and the total must add up.
2. Listing cards on the home page: location, rating, guests, price per night, badges.
3. Search and listing detail navigation.

## Skip
- Become a Host and Profile editing flows unless the PR changes them.
- Image loading failures from placeholder image hosts (expected in this demo).
