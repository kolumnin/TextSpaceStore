# Mobile DNS filter launcher

Open `mobile-dnsfilter.html` in a browser or publish it with GitHub Pages. It provides a mobile-sized launcher with:

- a direct download link for `personalDNSfilter.mobile.conf`
- a copyable profile URL
- concise import and Android setup steps
- no server-side code and no tracking dependencies

## Import

1. Download `personalDNSfilter.mobile.conf` onto the phone.
2. Open personalDNSfilter and use its import/restore action.
3. Disable Android Private DNS while the local filter is running.
4. Start the DNS proxy and verify connectivity.

The profile deliberately disables root mode and binds remote control to localhost. It is a generic modern-Android baseline, not a hardware-specific profile. Supply the exact phone model and Android version before applying OEM-specific battery, VPN, or IPv6 adjustments.
