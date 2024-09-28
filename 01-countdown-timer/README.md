# Countdown Timer

This is a countdown timer built with **Next.js**, **TypeScript**, and **TailwindCSS**. The application allows users to set a duration, start, pause, and reset the countdown timer with a clean and responsive interface.

## Features

- **Set Duration**: Enter the countdown duration in seconds.
- **Start Timer**: Begin the countdown.
- **Pause Timer**: Temporarily stop the countdown.
- **Reset Timer**: Return to the original duration.
- **Responsive Design**: Works seamlessly across devices.

## Technologies Used

- **Next.js**: A React framework for server-side rendering.
- **TypeScript**: For type safety and better development experience.
- **TailwindCSS**: For utility-first CSS styling.

## Usage

1. Enter the desired duration in seconds.
2. Click the **Set** button to initialize the timer.
3. Use the **Start**, **Pause**, and **Reset** buttons to control the countdown.

## Code Overview

The main component of the countdown timer is implemented in `Countdown.tsx`. Key parts include:

- **State Management**: Uses React hooks (`useState`, `useRef`, `useEffect`) for managing timer state and behavior.
- **Timer Logic**: The countdown is managed via `setInterval`, decrementing the time left every second.
- **UI Components**: Custom `Input` and `Button` components styled with TailwindCSS.

## Customization

You can customize the appearance and functionality by modifying the styles and timer logic in the `Countdown.tsx` component. TailwindCSS classes can be adjusted for different designs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by online countdown timer implementation.
- Built with [Next.js](https://nextjs.org/), [TypeScript](https://www.typescriptlang.org/), and [TailwindCSS](https://tailwindcss.com/).