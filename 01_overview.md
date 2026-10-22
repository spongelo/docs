# Laundry Room Queue System Overview

## Purpose

Provide a queue and status page for a laundry room with six machines, labeled 1–6. Users can see which machines are available, in use, or out of order, and who is using a machine or waiting.

## Registration and queue

- Anyone intending to use a machine registers on the queue site using their name; an account or other identity check is not required.
- The system assigns each registrant a queue number using a daily counter of people who register. The counter resets at midnight EST.
- If a machine is available, a user may choose any available machine.
- If all usable machines are occupied, users wait in first-come, first-served order.
- When a machine becomes available and someone is waiting, the next person is notified and has 10 minutes to claim it. If they do not claim it in time, they move back one position in the queue so the next person can proceed.

## Machine operation and status

- A user puts laundry into a machine and presses its start control. A hardware signal indicates that the cycle has started.
- A built-in machine signal indicates cycle completion after the machine has cycled a certain amount of water. The specific signal or threshold is provided by the machine; the system does not calculate a water amount.
- At cycle completion, the machine becomes available for the next user. The current user is expected to collect their washed laundry and leave.
- When a cycle completes, the machine and the queue page/device beep to alert the current user and the next person waiting.
- A weight sensor indicates whether laundry remains inside a machine after the cycle. This status does not delay the machine becoming available at cycle completion.
- The queue page updates machine availability and queue status when a cycle completes or a machine otherwise becomes available.

## Faults and maintenance

- A user or the system can report that a machine is faulty through the queue site.
- A machine with a reported fault is immediately marked out of order and cannot be selected or used until it is usable again.
- The system manager decides whether the machine needs maintenance or replacement and is responsible for clearing its out-of-order status after the issue is resolved.

## Not yet specified

- Whether users can cancel a registration or leave the waiting queue, and how that should affect their queue position.
