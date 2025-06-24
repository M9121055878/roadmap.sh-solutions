# overthewire.org

The description of each step is essentially derived from the previous step. For example, the solution to Natas1 is something that must be found in Natas0.

## natas0

He himself gave us the username and password.

> natas0

## natas1

1. Get the page's source.
2. Look the HTML comment.

        <!--The password for natas1 is 0nzCigAq7t2iALyvU9xcHlYN4MlkIwlq -->

## natas2

- You cannot right-click.
1. Get the page's source.
2. Look the HTML comment.

        <!--The password for natas2 is TguMNxKo1DSa1tujBLuZJnDUlCcUAPlI -->

## natas3

- There is nothing in the page's source.
1. Get the page's source.
2. In source you can find .

        <img src="files/pixel.png">

3. So we have a path named `files/` and access to that path is not blocked.
        
    in this path you can find : `users.txt`

        # username:password
        alice:BYNdCesZqW
        bob:jw2ueICLvT
        charlie:G5vCxkVV3m
        natas3:3gqisGdR0pjm6tpkDKdIWO2hSvchLeYH <-| The password is here.
        eve:zo4mJWyNj2
        mallory:9urtcpzBmH

## natas4