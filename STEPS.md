- npx create-next-app@latest ./

## App write
- Copy project id and paste into .env.local (PROJECT_ID)
- Integrate with your server > API key
    - Scopes > select all
    - Copy API Secret and past into .env.local (API_KEY)
- Create a new database
    - Copy ID and paste into .env.local (DATABASE_ID)
    - Creae collection 'patient' (copy id > paste .env.local (PATIENT_COLLECTION_ID))
    - Create collection 'doctor' (copy id > paste .env.local (DOCTOR_COLLECTION_ID))
    - Create collection 'appointment' (copy id > paste .env.local (APPPOINTMENT_COLLECTION_ID)
- Create a new storage bucket (NEXT_PUBLIC_BUCKET_ID)
- npm i node-appwrite
- Create the collections attributes
    - Then go to settings > permissions > allow any (select all)

## Add Sentry

## SMS with Appwrite > Twilio
- Messaging > Create provider > SMS > Twilio
    - Head over to Twilio website and create an account (copy account SID, auth token and sender number and paste into Appwrite config)

## Deploy with Vercel
