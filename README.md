
Built by https://www.blackbox.ai

---

# TV Live Panel

## Project Overview
The "TV Live Panel" is a web-based application designed to manage and display the live draw events for various lotteries and games. Built using HTML and styled with Tailwind CSS, it incorporates a responsive layout for a seamless user experience. The application allows users to manage live events, visualize audience engagement, and display results dynamically.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd tv-live-panel
   ```

2. Open `index.html` in your web browser to view the application.

## Usage
Upon opening the `index.html`, users are presented with a dashboard displaying information about the current draw sessions. The dashboard includes a navigation menu for accessing different sections like audience statistics, prize settings, comments, and photos.

- **Finalizar TV de hoje**: Ends the current session.
- **Configurações**: Accesses the settings page to make adjustments.
- **Sorteio NF Premiada**: Displays the lottery draw.

## Features
- **Dynamic Navigation**: Easy navigation between different sections of the application.
- **Live Audience Stats**: Real-time updates on audience engagement.
- **Responsive Design**: Adapts to different screen sizes for optimal usability.
- **Prize Management**: Manage and display winnings and draw results interactively.
- **Comment and Photo Section**: Allows users to upload and manage photos and comments associated with the draws.

## Dependencies
The project relies on the following external libraries:
- [Tailwind CSS](https://tailwindcss.com/) for styling.
- [Font Awesome](https://fontawesome.com/) for icons.
- [Chart.js](https://www.chartjs.org/) for graphing audience statistics.

## Project Structure
The project consists of several HTML files, a CSS file for common styles, and a structure as follows:

```
/tv-live-panel
|-- index.html                # Main dashboard page
|-- premio-bola-maior.html    # Page for managing prize draws
|-- palpite-premiado.html      # Page for displaying bet predictions
|-- audiencia.html             # Audience statistics page
|-- fotos-comentarios.html      # Page for managing comments and photos
|-- premiacoes.html            # Page for displaying awards
|-- sorteios.html             # Page for managing lottery draws
|-- editar-imagens.html        # Page for editing background images
|-- common.css                # Common styling for the application
```

The application is designed to be modular, allowing for easy updates and the addition of new features over time.

## Conclusion
This project serves as a scalable platform for managing live lottery events and audience interactions, utilizing modern web technologies to deliver a user-friendly experience.