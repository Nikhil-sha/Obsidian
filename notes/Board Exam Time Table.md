# Class 12 Board Examination Time Table - February 2026

|Date|Time|Subject|Gap (before)|
| - | - | - | - |
|18|2 - 5:15|Hindi|<span id="remaining"></span>|
|20|2 - 5:15|English|1|
|23|2 - 5:15|Math/Bio|2|
|25|2 - 5:15|Chemistry|1|
|27|2 - 5:15|Physics|1|

<script>
/**
 * Calculates the number of days remaining before a specified date.
 *
 * @param {Date} targetDate - The date to calculate days remaining for.
 * @returns {number} The number of days remaining.
 */
function daysRemaining(targetDate) {
  const today = new Date();
  const timeDiff = targetDate.getTime() - today.getTime();
  const daysDiff = Math.ceil(timeDiff / (1000 * 3600 * 24));
  return daysDiff;
}

const targetDate = new Date('2026-02-18');
const daysLeft = daysRemaining(targetDate);
remaining.textContent = daysLeft;
</script>