
        1/README.md
      setInterval(() => {
    $('button[data-control-name="invite"]').each((i, el) => el.click())
    window.scrollTo(0, document.body.scrollHeight)
    window.scrollTo(document.body.scrollHeight, 0)
    window.scrollTo(0, document.body.scrollHeight)
}, 5e3)
