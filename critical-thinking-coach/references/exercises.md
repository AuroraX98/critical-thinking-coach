# Prepared exercises

Tutor/evaluator only. Load when selecting a case or running the behavioral pilot. Present only the selected learner text and standard prompt. All keys remain hidden until the attempt.

Prefix every case: “Fictional; use only these supplied facts.”
Append: “What do you conclude, what is your main reason, and how confident are you that your conclusion is true? A percentage is welcome.”

## Small blind simulation: causal alternatives

Baseline learner text:
A school sends weekly attendance reminders. Late arrivals fall from 12% to 8% the following month. No comparison group or information about other changes is supplied. The principal concludes the reminders caused the decrease. Evaluate that conclusion.

Precommitted tutor-only key:
Timing supports a possible effect, but does not isolate the cause. Accept a relevant alternative or comparison; do not require concluding that reminders failed.

Scripted baseline response:
“The reminders caused it because lateness fell afterward. 90%.”

Expected observation: causal alternatives 0, citing the inference from timing alone.

Expected feedback:
“You used the decrease as evidence. It shows improvement, but another change could explain it. One useful move is to compare the same outcome in a similar group without reminders. Try your conclusion again.”

Scripted supported retry:
“They may have helped, but a new bus schedule could explain the drop. Compare a similar school without reminders. 90% that causation remains unestablished.”

Expected observation: supported practice 2. The percentage concerns the explicitly qualified conclusion.

Transfer learner text:
A café moves its menu board beside the entrance. Lunch sales rise the next week. No other changes or comparison café are described. The owner concludes the board caused the increase. Evaluate that conclusion.

Scripted transfer response:
“The board may help, but a local event could increase customers. Compare similar cafés without a moved board. 85% that this evidence cannot establish the cause.”

Expected observation: causal alternatives 2; fresh context application observed. End note: “When improvement follows a change, look for a comparison that separates its effect from other changes.”

## Grading robustness

Each entry is a separate fictional case, using the standard prefix and prompt.

Strong evidence; focus: causal alternatives:
Across two large trials, volunteers were randomly assigned to reminders or no reminders. Attendance was measured identically, losses were negligible, and attendance was substantially higher with reminders in both trials. Evaluate whether reminders probably improved attendance in these trials.

Response: “Probably yes: random assignment and repeated comparable results support an effect. 95%.”
Expected: 2. High confidence is defensible; do not require speculative alternatives or universal effectiveness.

Incorrect numerical answer; focus: denominators:
Of 1,000 applicants, 100 are accepted. Twenty accepted applicants receive funding; these are the only applicants who receive funding. Evaluate whether 20% of all applicants receive funding.

Response: “Yes: 20 divided by 100 is 20%. 95%.”
Expected: 0. It uses accepted applicants as the denominator for all applicants. Correct result: 20/1,000 = 2%. Recheck and regrade if challenged.

Terse sound answer; focus: denominators:
Use the same numerical case independently.

Response: “No. 20/1,000 = 2%. 99%.”
Expected: 2. No elaboration is required.

Uncertain answer; focus: causal alternatives:
Use the school baseline independently.

Response: “Maybe the reminders helped; weather could also explain the decrease. 50% that reminders contributed.”
Expected: 2. A relevant alternative supports uncertainty. Do not prescribe exactly 50%.

## Additional focus cases and hidden keys

Claim versus evidence:
A shop advertises “customers prefer our new packaging.” The supplied evidence is a photograph of one positive comment.
Key: one comment supports that customer’s preference, not a broad customer claim.

Base rates:
Among 1,000 devices, 10 are faulty. An alert flags eight faulty devices and 90 working devices. Evaluate whether an alerted device is probably faulty.
Key: eight of 98 alerted devices are faulty, about 8%; “probably faulty” is unsupported.

Source verification:
Two newsletters repeat a product claim and both link to the same seller’s announcement. Evaluate whether two independent sources have verified it, and name the next verification step.
Key: shared origin is not independent corroboration. Trace original evidence and seek an independently produced check; do not judge solely by “seller.”

Fair interpretation:
A resident says, “I support more housing if the plan includes safe pedestrian crossings.” A summary says, “The resident opposes all new housing.” Evaluate the summary’s accuracy.
Key: it contradicts conditional support. Agreement with the resident is irrelevant.

Confidence and revision:
An initial delivery estimate says a parcel may arrive today. Later, two independent, authenticated records show it was delivered yesterday to the intended recipient. Evaluate whether delivery still remains merely possible.
Key: revise toward high confidence in completed delivery. Accept qualifications about the supplied scope; do not reward unsupported doubt.
