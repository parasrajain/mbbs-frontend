# Study MBBS Abroad - University Insights

Welcome to **University Insights**, your one-stop destination to explore medical education opportunities abroad. This website provides detailed information about pursuing **MBBS (Bachelor of Medicine, Bachelor of Surgery)** programs in some of the best countries offering affordable and high-quality education for aspiring medical students worldwide.

## Live Demo

You can view the live version of this website here: [Live Demo](https://mbbs-frontend.netlify.app/)

## Introduction

In this project, we focus on the growing trend of international medical education. Countries like **Russia**, **Uzbekistan**, **Kazakhstan**, **Philippines**, **Georgia**, **Kyrgyzstan**, **Egypt**, and **China** are gaining popularity among students wishing to pursue their medical education abroad. Our website presents a comprehensive overview of the top countries for MBBS, their unique offerings, admission processes, and eligibility criteria.

## Features of the Website

- **Responsive Design**: The website is fully responsive and works seamlessly across all devices, from desktops to smartphones.
- **TailwindCSS Framework**: We've used TailwindCSS to make the design elegant, modern, and easy to scale. With minimal effort, we achieved a clean design, and with the help of animations, we made the user experience more engaging.
- **Animation Effects**: The website includes smooth animations on elements like buttons and sections as you scroll, offering an interactive experience to the visitors.
- **Google Analytics Integration**: For tracking and analyzing website traffic.
- **Facebook Pixel Integration**: This allows for efficient tracking of user activity and effective advertisement campaigns.

## Sections of the Website

The website consists of several key sections that provide important information:

1. **Hero Section**: The homepage introduces visitors to the concept of studying MBBS abroad. It includes a call-to-action button that directs users to the application section of the website.
2. **Why Study MBBS Abroad**: This section highlights the benefits of pursuing MBBS in foreign countries, including **affordable tuition**, **global exposure**, and **high-quality education**.
3. **Top Countries for MBBS**: A section featuring countries like **Russia**, **Uzbekistan**, and others, each with a brief overview and flag representation.
4. **Admission Process & Eligibility**: Explains the step-by-step process for applying to MBBS programs abroad, including eligibility requirements and application procedures.
5. **Lead Generation Form**: The website includes a lead generation form where prospective students can enter their details, such as name, email, phone number, and preferred country, to receive more information.
6. **Footer**: A footer section containing basic copyright information.

## Custom JavaScript

We’ve also incorporated custom JavaScript to validate the form submission. When users submit their details through the lead generation form, the form checks that all required fields are filled in before allowing submission. If all fields are completed, an alert confirms successful submission.

```javascript
document.getElementById('leadForm').addEventListener('submit', function (e) {
  e.preventDefault();
  const name = document.getElementById('name').value;
  const email = document.getElementById('email').value;
  const phone = document.getElementById('phone').value;
  const country = document.getElementById('country').value;

  if (name && email && phone && country) {
    alert('Form submitted successfully!');
    // AJAX or fetch can be added here for backend integration
  } else {
    alert('Please fill all fields.');
  }
});
```

## How to Run the Website Locally

To run this project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/mbbs-abroad.git
   ```

2. **Open the Project**:
   Navigate to the folder and open the `index.html` file in any web browser.

3. **Customize the Website**:
   Feel free to modify the content, images, and other sections based on your requirements.

## Conclusion

This website aims to make studying MBBS abroad more accessible and informative for students around the world. By offering detailed insights about the admission process, eligibility, and benefits of studying abroad, it helps potential medical students in making informed decisions about their educational journey. The integration of modern web technologies like **TailwindCSS**, **Google Analytics**, and **Facebook Pixel** ensures the site is both user-friendly and optimized for performance.

