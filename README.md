# AWS S3 Static Website with Route 53 Domain

Host your static website on AWS S3 and connect it to a custom domain with Route 53.

## Steps

1. **Register a Domain**
   - Use Route 53 to find and register a low-cost domain (e.g., `alfiyaproject.click`).

2. **Create an S3 Bucket**
   - Name your bucket after your domain (e.g., `alfiyaproject.click`).
   - Allow public access, as required for static website hosting.

3. **Upload Your Website**
   - Add your site files (like `index.html`) to the bucket.

4. **Enable Static Website Hosting**
   - In the S3 bucket settings, turn on static website hosting and set your index document.

5. **Set Permissions**
   - Make your site files publicly readable so they’re visible on the web.

6. **Connect Your Domain**
   - In Route 53, create a record to point your domain to your S3 website endpoint.

7. **Done!**
   - After DNS updates, your website will be live at your new domain.

---

## Screenshots

See included images for step-by-step visuals.

## Live Example

Visit: [alfiyaproject.click](https://alfiyaproject.click)

## Need Help?

Check `/docs/troubleshooting.md` or reach out via [your contact info here].
