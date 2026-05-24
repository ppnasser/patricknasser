---
title: 'Experience'
date: 2026-05-24
type: landing

design:
  spacing: '5rem'

# `username` references the folder under content/authors/

sections:
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="text-align:center;">
          <a href="/uploads/cv.pdf"
             target="_blank" rel="noopener"
             class="cv-cta inline-flex items-center gap-2 px-6 py-3 rounded-lg font-medium
                    bg-primary-600 hover:bg-primary-700 text-white no-underline shadow
                    transition-colors duration-200">
            ⬇️ Download CV
          </a>
        </div>
    design:
      columns: '1'

  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'Jan 2006'
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills
      username: me
  - block: resume-awards
    content:
      title: Awards & Certifications
      username: me
  - block: resume-languages
    content:
      title: Languages
      username: me
---
