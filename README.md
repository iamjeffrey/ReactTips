# ReactTips

- Tracking Scroll position
https://dev.to/n8tb1t/tracking-scroll-position-with-react-hooks-3bbj


- Meta setting
<meta
    name="viewport"
    content="width=device-width, initial-scale=1, user-scalable=0, maximum-scale=1, minimum-scale=1"
/>


Object.defineProperty(window, 'innerWidth', {writable: true, configurable: true, value: 200})
window = Object.assign(window, { innerWidth: 500 });
