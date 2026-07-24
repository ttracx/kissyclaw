# THOX GitHub Agent Team (σελίδα γέφυρα)

Δείτε το [αγγλικό έγγραφο πηγής](../../thox-agent-team.md) για την πλήρη προδιαγραφή.

## Review coverage

Η ροή καλύπτει issues, σχόλια issues, pull requests, χειροκίνητη επικύρωση και ημερήσιο έλεγχο πολιτικής.

## Safe merge gates

Συγχώνευση μόνο όταν περάσουν όλοι οι απαιτούμενοι έλεγχοι, το branch protection την επιτρέπει, το PR δεν είναι draft, το head SHA ταιριάζει και οι ευαίσθητες αλλαγές έχουν ανθρώπινη ανασκόπηση.

## Branch pruning

Διαγράφονται μόνο συγχωνευμένα feature branches του ίδιου repository που δεν είναι default ή protected και δεν αναφέρονται από άλλο ανοιχτό PR.
