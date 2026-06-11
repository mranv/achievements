# Achievements

A collection of shell scripts to achieve 100% of API-accessible GitHub achievements. Because, you know, we all have endless hours to kill collecting digital badges.

## Prerequisites

- **GitHub CLI (`gh`) Installed**
  If you haven't installed the GitHub CLI by now, do you even code, bro?

- **Authentication**
  Run `gh auth login` and make sure you can actually log in. I believe in you. Sort of.

## Instructions

### Setup

To run these scripts, you'll need to set up a local version of this repository. Because forking repos and running shell scripts is just so much fun.

1. **Fork the Repository**
   Fork the [main repository](https://github.com/nathanielop/achievements) on GitHub. It’s not like you have anything better to do.

2. **Clone and Initialize the Repository**
   Fire up your terminal and punch in these commands:

   ```bash
   mkdir achievements
   cd achievements
   git init
   git remote add origin git@github.com:[YOUR USERNAME HERE]/achievements.git
   ```

   **Warning:** If your Git isn’t set up with your GitHub account, do us all a favor and follow the guide [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh). Because, obviously, this is rocket science.

### Running Achievement Scripts

Gain any individual achievement by running the name of that achievement directly. It's like magic, but for people who don’t believe in shortcuts.

#### Example

To unlock the "pullshark" achievement, run:

```bash
bash pullshark
```

Or, to waste your life away getting all achievements, run:

```bash
bash all
```

**Warning:** This might take several hours. Perfect for when you have absolutely nothing better to do. Just let it run in the background while you contemplate your life choices.

### Running Achievement Scripts, But With Guardrails

If your fork has ever stared deep into `gh pr create` and wondered which
repository it was about to bless with badge-generation nonsense, use the safe
wrappers instead:

```bash
cp .env.safe.example .env.safe
bash bin/safe-all
```

The safe wrappers create or reuse a private repository under your own account,
set the GitHub CLI default repository explicitly, verify that the target is
private and self-owned, and pass `--repo`, `--base`, and `--head` to every pull
request command. This is the painstakingly idiot-resistant path for anyone who
prefers their achievement archaeology not to become an accidental upstream PR.

---

### Professional Commitment

As a cybersecurity professional, I'm here to protect your digital assets with the best security solutions. Because who doesn’t love integrating robust security measures and ensuring resilient applications for everyone?

---

# Contact Information

**Anubhav Gain**
Email: [iamanubhavgain@gmail.com](mailto:iamanubhavgain@gmail.com)
