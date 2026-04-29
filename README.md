This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

# Screenshots
## Dashboard
![alt text](/screenshots/image.png)

## Free style pipeline
![alt text](/screenshots/image-1.png)
![alt text](/screenshots/image-2.png)

## Console Output - Success
![alt text](/screenshots/image-3.png)
## Console Output - Failure
![alt text](/screenshots/image-4.png)

## Pipeline Script
![alt text](/screenshots/image-5.png)

```bash
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Manikandan'
            }
        }
    }
}
```
## Console output - Success
![alt text](/screenshots/image-6.png)

## Console output - Failure
![alt text](/screenshots/image-7.png)

## Pipeline Script from SCM
![alt text](/screenshots/image-8.png)

## Console output - Success
![alt text](/screenshots/image-9.png)
![alt text](/screenshots/image-10.png)
![alt text](/screenshots/image-11.png)
![alt text](/screenshots/image-12.png)

### Pipeline overview
![alt text](/screenshots/image-15.png)

## Console output - Failure
![alt text](/screenshots/image-13.png)
![alt text](/screenshots/image-14.png)


## GitHub link: [`ManikandanJN`](https://github.com/ManikandanJN/jenkins-pipeline-demo.git)


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.


