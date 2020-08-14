Place your built "RMS Service" in best-service/bin/service.

To run best service

- Run App.bat

- Run "run.bat"
- Edit service-app.properties
  - database url: localhost > [192.168.1.47](https://l.workplace.com/l.php?u=http%3A%2F%2F192.168.1.47%2F&h=AT1OwXE5-BGKajVfu4LlNHEKhdbPo2kk1obN52B0CN_YVSM3ri5GR-df6ueR1-o4qsHRA3Cd5b82mjaEvpjzPm4wnhBDMqlVY-BAJjbeGIuxZcc_BBG6M3rJk6SwEuxPofJFbFWcgFx5RPP9lpx6QZ1Nz4G_T9EF)

To run job RMS

- Make sure your ConnectionString.xml was point to your datafile in MYOB. In MYOB, new card "DEFAULT" and VAT (LISts/TaxCode) were inserted.

- 192.168.1.47:8081/phpmyadmin / root - Hde@123
- open database hd-report-ho
- open table job
- sort create date > newest RMS
- switch inactive = 0; updated = 1

