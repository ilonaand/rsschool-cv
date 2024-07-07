
## rsschool-cv

### My fullname is Ilona Andilevko
### Contacts: 

ilonaand@gmail.com

@Илона#4323(@ilonaand)

### About me: 
I am a software engineer with 10+ years of professional experience.

### Skills:
- Strong knowledge of js, ts, Delphi, VBScript, Object Pascal
- Extensive expertise in Node JS and technologies related to it such as Express, Koa. 
- Experience of using different databases like Firebird, MSSQL, Oracle, MySql. 
- Skills to work with different programming paradigms. 
- Self-disciplined, highly motivated and a quick learner. 
- Ability to work in a team as well as individually.

### Code example:

```
    export const readTextFile = async <T>(
        fileName: string,
        start: number | undefined,
        end: number | undefined,
        ): Promise<T | string> => {
        const check = await checkFileExists(fileName);

        try {
            const streamRead = createReadStream(fileName, { encoding: 'utf8', start: start, end: end });
            const data = [];
            for await (const chunk of streamRead) {
            data.push(chunk);
            }
            return data.join('').toString();
        } catch (err) {
            return `Ошибка чтения файла ${fileName} - ${err} `;
        }
        };
```

    
### Recent and major projects:

[GDMN platforrm](https://github.com/stasgm/gdmn-mob.git) The server part of the platform for mobile applications to automate business processes 

### Education: 

- Belarusian National Technical University
    - Applied Mathematics
- Course on RsSchool
    - NodeJS 2022 Q4 [Сертификат](https://app.rs.school/certificate/aoqg5bu1)
### Languages: 
- A2 (B1 in process…)
