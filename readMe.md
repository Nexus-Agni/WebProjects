# Genius Clone

This project is a clone of the Genius website, a platform for song lyrics and musical knowledge. It is built using the following tech stack:

- HTML
- Custom CSS

![Screenshot of the project](https://private-user-images.githubusercontent.com/118368089/292767545-3b141dd6-4b0d-491a-9efe-386b4a5bd9a0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MTk1OTAsIm5iZiI6MTcwMzUxOTI5MCwicGF0aCI6Ii8xMTgzNjgwODkvMjkyNzY3NTQ1LTNiMTQxZGQ2LTRiMGQtNDkxYS05ZWZlLTM4NmI0YTViZDlhMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIyNVQxNTQ4MTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yYmQ3MjM5NmMxNjllZWY0YzU4NmM0NzZlNzQ1ZWE1ZTZmYzNiMzM4ZjcxM2M1ZWFjYjE5MThjOWQwMmNhN2UwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Dzrpcmt083Jt5506AejzaPzjuBUo-_YC_AD-uBWGLck)
![Screenshot of the project](https://private-user-images.githubusercontent.com/118368089/292767550-171810ac-e399-4bb4-aa36-a93cee595b4a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MTk1OTAsIm5iZiI6MTcwMzUxOTI5MCwicGF0aCI6Ii8xMTgzNjgwODkvMjkyNzY3NTUwLTE3MTgxMGFjLWUzOTktNGJiNC1hYTM2LWE5M2NlZTU5NWI0YS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIyNVQxNTQ4MTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yZjRmOTI2NWMxMzk0OTJlMTYxNjU0ODZhYjFiNWJlODU5ZGNmMmRhMjBlZjRmMmNiMjAyZWFhMWIxMzg1NGQyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.kTKHbQAlRKfbPjlNpTEfHhVS03huD49IPlPwKeHrqAY)
![Screenshot of the project](https://private-user-images.githubusercontent.com/118368089/292767553-44cecdd3-d5c8-4ba9-9da2-98c79f66ef67.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MTk1OTAsIm5iZiI6MTcwMzUxOTI5MCwicGF0aCI6Ii8xMTgzNjgwODkvMjkyNzY3NTUzLTQ0Y2VjZGQzLWQ1YzgtNGJhOS05ZGEyLTk4Yzc5ZjY2ZWY2Ny5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIyNVQxNTQ4MTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00MjhjYzQ3MWZlMzRiNWUwODFhNzM1YzFmMzkzM2NjNjEzMTM5MjNmMGMxYmY4ZDk1YTNjNjU2OWRlMGI1MTIwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.lsM-LLHO8E2mnCAoAP4xzmaI-zSjiHx6lNGvfFmF3lc)
![Screenshot of the project]( https://private-user-images.githubusercontent.com/118368089/292767558-3b20a420-1b01-4f6f-bc25-ebe998751376.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDM1MTk1OTAsIm5iZiI6MTcwMzUxOTI5MCwicGF0aCI6Ii8xMTgzNjgwODkvMjkyNzY3NTU4LTNiMjBhNDIwLTFiMDEtNGY2Zi1iYzI1LWViZTk5ODc1MTM3Ni5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjI1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIyNVQxNTQ4MTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NjMyYmM5NGM3MDgxYWUwMzE2YWI3MTQwMzA5ZTVhODU1MzdiMDkwNzc2ODE1MmNlODM4N2QxZGE4ZmI3MGVmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.sjPJXsl6oYZ_AmFBShGhLrNHecMLlFmosZI-9SeqOKg)