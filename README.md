# PI Hole Blacklist

This repository provides a comprehensive blacklist for PI Hole, aimed at blocking unwanted and malicious domains.

## Installation

To add this blacklist to your PI Hole:

1. Open your PI Hole admin dashboard.
2. Go to **Group Management > Adlists**.
3. In the **Address** field, paste the following URL:

   ```
   https://raw.githubusercontent.com/oytunistrator/pihole-blacklist/refs/heads/main/blacklist.txt
   ```

4. Click **Add** to include this blacklist in your setup.
5. Update your PI Hole gravity list by running the following command in your PI Hole terminal (if required):

   ```
   pihole -g
   ```

## Notes

- This blacklist is regularly updated to enhance protection.
- Feel free to contribute or suggest new domains to be added to the list.
