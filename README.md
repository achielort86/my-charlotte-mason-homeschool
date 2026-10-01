# My Charlotte Mason Homeschool V3

Includes email/password login, Parent and simplified Child views, cloud-synced lesson completion, weekly matrix, curriculum, portfolio/narration, parent notes, CM tools, and mobile-friendly design.

Curriculum preloaded: The Nursery Book of Bible Stories; Westminster Shorter Catechism; Laying Down the Rails; The Seven Little Sisters; Winnie-the-Pooh / The House at Pooh Corner; Ring O' Roses / A Child's Garden of Verses; McGuffey's; The Monkey and the Turtle; Tagu-taguan; Pakitong-kitong; Kinder math curriculum / Arithmetic for Children.

Setup:
1. Supabase project.
2. Run supabase_schema_v3.sql once (skip if these tables already exist and policies were already created).
3. Host index.html on an HTTPS static host such as GitHub Pages.
4. Open the site, enter Project URL + Publishable Key, Save connection.
5. Sign in.

Never put an sb_secret or service-role key in the browser. V3 has one authenticated account with two views; it is not a separate child identity.
