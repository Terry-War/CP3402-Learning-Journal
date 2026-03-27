# Week 05 - learning Journal - WordPress Child Themes
## Learning Activities & Resources

This week I worked on creating a child theme for my existing WordPress website. The goal was to make design changes without editing the original parent theme files.

At the start, I found this task a bit confusing and honestly a little frustrating. It felt more technical than the usual WordPress work, especially having to create files manually and make sure everything was named correctly. I was worried that if I made a small mistake (like the wrong template name), the whole theme wouldn’t work.

Once I followed the steps carefully, it started to make more sense. After creating the child theme folder, adding the `style.css` file, and setting up the `functions.php`, I activated the theme and saw the changes appear. That was a really satisfying moment and made the process feel much easier.

I then added several visible customisations such as background colour, header styling, navigation colours, button styles, and footer changes. Seeing these changes update on the live site made it feel more like real development work rather than just using the WordPress dashboard.

### Step-by-step process to create the child theme
1. Go to the WordPress files and open `wp-content/themes/`.
2. Create a new folder for the child theme (e.g. `twentytwentfive-child`).
3. Inside the folder, create a file called `style.css`.
4. Add the required theme header at the top of `style.css`, including the `Template` name that matches the parent theme exactly.
5. Add custom CSS underneath to change things like colours, buttons, and layout.
6. Create another file called `functions.php` in the same folder.
7. Add code to load (enqueue) the parent and child stylesheets.
8. Go to the WordPress dashboard → Appearance → Themes.
9. Activate the new child theme.
10. Check the website and confirm that the changes are visible.

## Estimated Hours
1-2 hours

## Content Insights
This task helped me understand how WordPress themes actually work behind the scenes. Before this, I mainly used the dashboard and plugins, but this showed me how themes are structured using files.

I learned that the most important part is getting the setup correct, especially the `Template` line in the `style.css`. If that is wrong, the child theme won’t work at all. I also learned how the `functions.php` file is used to properly load styles.

The biggest takeaway was that child themes are a safe way to customise a website, because changes won’t be lost when the parent theme updates.

## Career
This felt much closer to real web development work compared to previous tasks. It gave me experience working directly with theme files instead of just using the WordPress interface.

This is useful for future careers because many businesses use WordPress, and knowing how to create and customise child themes is a valuable skill for web development and design roles.

## Employability
This task improved my attention to detail, because even small mistakes could stop the theme from working. It also helped with problem-solving, especially when something didn’t load correctly and I had to figure out why.

It also showed that I can learn new technical concepts independently. At first it was confusing, but by working through it step by step I was able to complete the task successfully.

I also used LinkedIn to reflect on this learning experience and share what I worked on. Posting about the task helped me think more clearly about what I learned and how to explain it to others. It also helps build a professional online presence, which is important for future job opportunities.

## Learning insights
At the start, I felt unsure and a bit overwhelmed because this was more technical than what I was used to. However, once I understood the structure and purpose of each file, it became much easier.

The biggest insight for me is that breaking tasks into small steps makes them much more manageable. I also realised that seeing visible results (like the design changes) helped build my confidence quickly.

Overall, this task helped me feel more comfortable working with WordPress at a deeper level, not just through the dashboard but also through code and file structure.

### Additional Activity – LinkedIn Usage

As part of this week, I also used LinkedIn to share a post about my experience using local hosting for WordPress development.

The post itself was a short summary of what I learned using Local by Flywheel, but the main focus for me was understanding how LinkedIn can be used as a professional tool. It allowed me to reflect on my learning, communicate it clearly, and present it in a way that could be seen by others in the industry.

At first, I felt a bit unsure about posting, as it can feel awkward sharing your work publicly. However, once I wrote the post, it felt more natural and gave me more confidence in explaining what I had learned. It also made me realise that LinkedIn is not just for job searching, but also for documenting progress and building a professional identity over time.

I explored some of the features of LinkedIn, including creating posts, using hashtags, and structuring content in a clear and readable way. These features help improve visibility and make posts more engaging for others.

From a career perspective, LinkedIn seems like a useful platform for showcasing skills, sharing projects, and demonstrating ongoing learning. It can act as a digital portfolio and help connect with others in the industry.

Overall, using LinkedIn helped me reflect more on my work and made me more aware of how important it is to communicate skills and experiences in a professional way.

linkedin post link
https://www.linkedin.com/posts/terry-keenan-warland-9858703b7_recently-ive-been-experimenting-with-local-share-7439130282206662656-ZBWz?utm_source=share&utm_medium=member_desktop&rcm=ACoAAGXAzHUBVCe_60_e5vnB5_I3wfleuW6zrpg