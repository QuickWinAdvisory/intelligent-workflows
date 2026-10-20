# Setup prompt

Attach `kontrol-panel.html` to a Claude chat and paste:

> Publish the attached kontrol-panel.html as a new private artifact called "Kontrol Panel". Don't change the code. Declare these capabilities:
> - db with rules `[{"path":"","read":"owner","write":"owner"}]`
> - user with scopes `["profile"]`
> - mcp with servers Gmail (`search_threads`), Google Calendar (`list_events`) and Claude Code Remote (`fire_trigger`)
> - downloads
> - sample
>
> If Gmail or Google Calendar isn't connected yet, tell me which connector to add first.

To change something later, attach the updated file and ask Claude to republish it to the same artifact link.
