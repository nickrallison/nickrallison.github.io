---
layout: page
title: Note Linker
img: assets/img/note_linker/cover.png
importance: 5
category: fun
---


<div class="repo p-2 text-center">
  <a href="https://github.com/obsidian-note-linker-with-previewer">
    <img
      class="repo-img-light w-100"
      alt="obsidian-note-linker-with-previewer"
      src="https://github-readme-stats.vercel.app/api/pin/?username=nickrallison&repo=obsidian-note-linker-with-previewer&theme={{ site.repo_theme_light }}&show_owner={{ show_owner }}&description_lines_count={{ max_lines }}"
    >
    <img
      class="repo-img-dark w-100"
      alt="obsidian-note-linker-with-previewer"
      src="https://github-readme-stats.vercel.app/api/pin/?username=nickrallison&repo=obsidian-note-linker-with-previewer&theme={{ site.repo_theme_dark }}&show_owner={{ show_owner }}&description_lines_count={{ max_lines }}"
    >
  </a>
</div>

This is a plugin to find possible links between notes and then to link them together. Written in with a combination of Rust compiled down into webassembly and typescript.

It uses a parser and a custom grammer I wrote to exclude code blocks, latex blocks, and existing links. It is also used to selectively avoid linking italicized or bold text.

<div class="embed-container">
  <iframe
      src="https://github.com/user-attachments/assets/5c3170db-0e39-4ac1-83bb-f0a183b30478"
      width="854"
      height="480"
      frameborder="0"
      allowfullscreen="true">
  </iframe>
</div>