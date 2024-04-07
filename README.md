# Devbox & Tmux & tmuxp

This demo repo shows the powerful combination of:
- Devbox ([github.com/jetpack-io/devbox](https://github.com/jetpack-io/devbox))
- Tmux ([github.com/tmux/tmux/wiki](https://github.com/tmux/tmux/wiki))
- tmuxp ([github.com/tmux-python/tmuxp](https://github.com/tmux-python/tmuxp))

## Getting started

All you need is Devbox installed:

```bash
curl -fsSL https://get.jetpack.io/devbox | bash
```

Then, run the following command to start a Tmux session with 4 panes. At the top right, you'll see the dev server running.

```bash
devbox run tmux
```

### Help, how do I exit Tmux?

No worries, we all got stuck in Tmux at first :-). Either kill your terminal or run the following key sequence:
- Ctrl + B
- Shift + &
- y

### Non-tmux team members

For anyone who isn't familiar or doesn't want to use Tmux, they can use Devbox as usual.

To start all services required by the project:

```bash
devbox services up
```

To start a shell with all necessary dependencies:

```bash
devbox shell
```

## Why?

In most software projects, you have to run multiple commands to get the project environment configured and ready for local development. Things like databases, maybe a database UI, backend services, web applications. Maybe it's all combined in `docker-compose up`, maybe not. In any case though, it is very likely you need more than one terminal window.

Use this repository as a template to configure your own project and all services you need to start.

## Improve your project developer experience!

Contact me via DM on X ([@mootoday](https://x.com/mootoday)). I review your developer experience and reduce onboarding to minutes – guaranteed!

