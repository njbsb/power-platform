# 📊 Key Entities

## `LeadRequest`

- `LeadID` (GUID) – Primary Key
- `FullName` (Text)
- `Email` (Text)
- `Status` (Choice: New, Validated, Rejected)

## `LeadAssignment`

- `AssignmentID` (GUID)
- `LeadID` (Lookup → LeadRequest)
- `OwnerID` (User)
