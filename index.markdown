---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<div id="headerIMG">
    <img style="border:none;" src="{{ site.url }}{{  site.baseurl }}/assets/images/lamp-logo.png" alt="Screenshot of Booth displaying a list of Sessions" height=200>
    <div class="row">
        <div class="column">
            <img src="{{ site.url }}{{  site.baseurl }}/assets/images/booth-sessions.png" alt="Screenshot of Booth displaying a list of Sessions" height=400>
        </div>
        <div class="column">
            <img src="{{ site.url }}{{  site.baseurl }}/assets/images/booth-map.png" alt="Screenshot of Booth displaying a map view of sessions" height=400>
        </div>
    </div>
</div>

### What is Booth?

Booth is a central platform to host and join study sessions that are going on in your school. Booth is a powerful tool for students who strive in a social environment; it allows you and your peers to help one another in the difficult classes that you will encounter as you progress through your degree. Furthermore, Booth is a way to promote collaborative studying as well as making it easier to engage in a learning environment on campus.


### How can Booth help me?

Many students will undoubtedly encounter challenging classes, topics, and even assignments where they can no longer progress forward despite the best of their abilities. Studies have shown that students who reach out for help are more likely to succeed in their classes. There are many ways for struggling students to get help: attend TA hours, post a question on Piazza, or search online for answers. In contrast, Booth highlights and promotes the in-person aspect of an educational and social environment. Booth gives students the ability to easily look for ongoing study sessions in their area. By providing a more efficient and effective access to this specialized environment, students are able to ask for help from their peers and make more meaningful relationships throughout their college career.

### How does Booth work?

Booth uses Firebase to uphold a majority of the features the app provides. Booth uses realtime database to make sure the UI is up to date with the latest events going on in your school as well as Firestore to store usage data and images that are uploaded in Booth. We also use multiple APIs that enhances the Booth experience such as [Google Maps API](https://developers.google.com/maps) and [University Domains API](https://github.com/Hipo/university-domains-list)

<img src="{{ site.url }}{{  site.baseurl }}/assets/images/booth-diagram.png" alt="Diagram of Booth's infrastructure" style="object-fit: contain; max-width: 100%;">


