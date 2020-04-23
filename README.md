### Tuned profile to be used on IBM Spectrum Scale Erasure Code Edition (ECE)


NOTE: For detailed information on how to add this profile to the system please check [Chapter 2. Customizing Tuned profiles](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/monitoring_and_managing_system_status_and_performance/customizing-tuned-profiles_monitoring-and-managing-system-status-and-performance)




##### Once you have the directory spectrumscale-ece from this repo:

- copy it into */etc/tuned/*
- start if not already running tuned daemon *systemctl start tuned*
- enable tuned daemon *systemctl enable tuned*
- apply the profile *tuned-adm profile spectrumscale-ece*
- verify the system is compliant with the profile *tuned-adm verify*



