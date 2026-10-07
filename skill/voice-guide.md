# Voice guide: how I talk upstream

<!--
THIS IS A CARRY-OVER SLOT, not a new hole. You wrote this guide in
week 2; paste your filled week-2 voice-guide.md here, whole. It is not
re-authored and it is not graded as new work this week.

Then reread it with the plan comment in mind. Your claim and repro
comments promised and reported; a plan comment commits you to an
approach in front of the people who maintain the code. If your rules
do not cover that register (for example: how you state an approach you
are not certain of, or how you respond when a maintainer already
suggested a direction), extend the guide with what it needs. Extending
is allowed and encouraged; starting over is not required.

Live mode reads this file before your plan comment goes out and
reports any rule your draft breaks. Eval mode ignores it entirely,
because your voice is yours and carries no gold labels.
-->

## Who I am in threads

<!-- Paste your week-2 section here. -->
I'm an early-career dev doing this as my first open-source contribution, working through CodePath.org. I've reproduced but not yet fixed this codebase before. Readers should expect me to be precise about what I checked and cautious about what I claim: I am not a maintainer, nor an expert in this repo. I am proposing a plan, not announcing a fix.


## Rules I write by

<!-- Paste your week-2 rules here, wrong/right pairs and all. Add any
rule the plan-comment register needs that your week-2 comments did
not. -->

- Rule: no bare confirmations 
  - Wrong: "Can confirm, seeing this too!" 
  - Right: "Reproduced on `version` with `artifact`; differs from the report in `X`."
- Rule: no timeline promises 
  - Wrong: "I'll have a fix up by Friday." 
  - Right: "Next I'm going to look at [specific next step]."
- Rule: name the version explicitly 
  - Wrong: "using the latest version" 
  - Right: "v3.2.4 (pip), Python 3.12.4."
- Rule: hedge only with evidence 
  - Wrong: "I'm 100% sure this is the root cause." 
  - Right: "This looks consistent with [X], but I haven't ruled out `Y`."
- Rule: disclose AI use when the repo asks for it 
  - Wrong: (silence) 
  - Right: "I used an AI assistant to help organize this report; I ran and verified every step myself."
- Rule: name the files and the test
  - Wrong: "I'll make a fix and test it."
  - Right: "Touching sync_controller.go only. I'll re-run my repro steps; step 3 should show the pushed color."
- Rule: don't promise a PR, ask first
  - Wrong: "Will send a PR shortly."
  - Right: "If this approach looks right to you, I'll open a PR. Happy to adjust first."

## Things I never post

<!-- Paste your week-2 list here; extend it if planning tempts you
toward new ones (overpromised timelines are the classic). -->


- just installed and got the same issue" with no repro
- claiming certainty about root cause without an artifact
- piggybacking ("same as above, can confirm") on someone else's repro
- promising a PR before the maintainer has seen the approach