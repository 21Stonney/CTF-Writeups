# HTTPS 101 (Web CTF)

## Challenge Description
i was provided with a certificate file named `my-selfsigned.crt`.  
The goal is to inspect the certificate and discover information about the website it was issued for, as well as the public key algorithm used.

---

## Steps Taken
1. **Checked the file type**

   ```file my-selfsigned.crt```

2. **Viewed the certificate details**

  ``` openssl x509 -in my-selfsigned.crt -text -noout```

3. **Identified the intended website**

4. **Checked the public key algorithm**

5. **Reviewed the signature algorithm**
