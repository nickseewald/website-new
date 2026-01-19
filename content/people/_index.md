---
title: Lab Members
type: landing

sections:
  - block: team-showcase
    content:
      title: Lab Members
      subtitle: World-class researchers advancing science
      text: Our diverse team brings together expertise from multiple disciplines.
      user_groups:
        - PI
        - Principal Investigators
        - Postdoctoral Researchers
        - Biostatistics Students
        - name: Alumni          # optional per-group sort override
          sort_by: graduation_year
          sort_ascending: false
      sort_by: 'graduation_year' # legacy 'Params.' prefix optional
      sort_ascending: false
    design:
      show_role: true
      show_organizations: true
      show_interests: true
      max_interests: 4   # set 0 to hide interests even if provided
      align: left      # or "left" to align header + CTA left
      max_columns: 4     # 2, 3, or 4
      show_social: true
      show_empty_groups: false # show a placeholder when a group has no members
      # Section background color (CSS class)
      css_class: "bg-gray-50 dark:bg-gray-900"
---
