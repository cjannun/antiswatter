How to Run Anti-Swatter Application

To view:
Player Report Page (viewer/fan interface): run "npm run dev" in the "AntiSwatReporr" file
  - report potential swattings for existing streamers
  - optionally enter your Liquid+ Number to recieve Liquid+ points
  
Add Player Page (streamer/org interface): run "npm run dev" in the "AntiSwatReport" file
  - Add a new streamer to your organization (Name, Address)

Player's Status Page (streamer/org interface): run "vercel" in the "mongodbvercel" file
  - View all streamers currently in your organization
  - Updated report count for each streamer
  - Click "Police Dept" to find the closest police department to their location

Ports: 8000, 8080, 8081, 8082

Currently, streamers/players must be manually deleted by deleting their objects from the MongoDB cluster called "Test 2"
