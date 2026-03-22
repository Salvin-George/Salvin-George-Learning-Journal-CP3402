## Learning Activities & Resources

- This week I focused on learning how to create a WordPress child theme and how themes are structured. I followed the WordPress documentation to understand how child themes inherit from parent themes.

- I also explored how to run WordPress using Docker, which allowed me to set up a local development environment that is consistent and reproducible.

## Resources used:

- Read the WordPress Developer documentation on child themes  
    - https://developer.wordpress.org/themes/advanced-topics/child-themes/



## Estimated Hours

- About 4 hours


## Content Insights

This week I learned how WordPress child themes work and why they are important. A child theme allows you to modify the appearance and functionality of a site without directly editing the parent theme files. This is important because updates to the parent theme would otherwise overwrite any changes made.

I also learned how WordPress uses the `style.css` file not just for styling, but also to register the theme using the header comment. The `Template` field is critical because it links the child theme to its parent theme.

Another key concept was enqueueing styles using `functions.php`. Instead of directly importing CSS, WordPress uses a structured system (`wp_enqueue_style`) to manage dependencies between stylesheets. This ensures the parent styles load before the child styles.

Using Docker to run WordPress locally also helped me understand how development environments can be standardised. It separates the application from my local machine setup, making it easier to manage and reproduce.


## Career/Employability/Learning Insights

Working with Docker also highlighted the importance of modern development workflows. Being able to spin up a full WordPress environment quickly is a valuable skill and allowed me to eaily test changes and with directly with the wordpress files.

From an employability perspective, understanding child themes is useful because it reflects how developers safely customise production websites. It shows an awareness of maintainability and best practices, rather than making direct changes that could break a site during updates.
