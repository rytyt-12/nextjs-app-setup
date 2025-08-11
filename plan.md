# Project Plan for AfroSalon Clone with Interactive Map and User Features

## Overview
Create a Next.js 15+ TypeScript project replicating the AfroSalon UI style with the following features:
- Interactive map using Leaflet with OpenStreetMap
- User location access to show nearby salons
- Booking system with messaging for acceptance/refusal by salon profiles
- User profile management: photo upload, video upload, username/salon name change
- Video upload support
- Messaging system for order management
- Responsive and accessible UI using Tailwind CSS and shadcn/ui components
- Package project as a downloadable zip file

## Project Structure
- src/app/
  - page.tsx (main landing page with map and salon list)
  - profile/ (user profile management pages)
  - bookings/ (booking and messaging system pages)
- src/components/
  - Map.tsx (Leaflet map component)
  - SalonCard.tsx (salon listing card)
  - ProfileForm.tsx (profile edit form)
  - BookingMessage.tsx (booking message UI)
- src/hooks/
  - useGeolocation.ts (custom hook for location access)
- src/lib/
  - api.ts (mock API functions for salons, bookings, user data)
- public/
  - placeholder images and icons

## Features to Implement
1. Interactive Map
   - Leaflet map centered on user location or default
   - Markers for salons with popup info
2. Salon Listing
   - Search and filter salons by distance and services
   - "Reserve" button to book a salon
3. Booking System
   - User can send booking requests
   - Salon profile can accept or refuse bookings
   - Messaging UI for booking status
4. User Profile
   - Upload/change profile photo
   - Upload videos
   - Change username/salon name
5. Video Upload
   - Support video file upload with preview
6. Location Access
   - Request user permission for geolocation
   - Show nearby salons based on location
7. Responsive UI
   - Mobile and desktop friendly
   - Dark/light mode support

## Additional Notes
- Use React Hook Form for forms
- Use Sonner for toast notifications
- Use Tailwind CSS for styling, no external icon libraries
- Use mock backend (local state or JSON) for demo purposes
- Prepare project for easy zip download

## Next Steps
- Implement base Next.js project with required dependencies
- Build core UI components and pages
- Integrate Leaflet map and geolocation
- Implement booking and messaging logic
- Implement profile management features
- Test responsiveness and accessibility
- Package project as zip for download
