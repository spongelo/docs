# Machine Status and Lifecycle

The laundry room has six machines, identified as 1 through 6. The queue page shows which machines are available, in use, or out of order.

## Use lifecycle

1. A user registers on the queue site.
2. If a machine is available, the user chooses one. If all usable machines are occupied, the user waits in queue order.
3. The user puts laundry into the selected machine and presses its start control.
4. A hardware signal indicates that the cycle has started; the machine is shown as in use.
5. A built-in machine signal indicates cycle completion.
6. At cycle completion, the machine becomes available. The current user collects their washed laundry and leaves.
7. If someone is waiting, the next person is notified and has 10 minutes to claim the machine.

## Laundry remaining after completion

A weight sensor indicates whether laundry remains inside a machine after its cycle. This indication is separate from availability: the machine becomes available at cycle completion, and remaining laundry does not delay that status.

## Fault status

When a fault is reported, the machine is marked out of order and cannot be selected or used until the system manager clears that status after resolving the issue.
