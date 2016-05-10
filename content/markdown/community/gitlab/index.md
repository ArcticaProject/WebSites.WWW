.. pub: 1
.. description: The Arctica Project's Development Tools.
.. title: The Arctica GitLab Server

# The Arctica GitLab Server

## Signing up

The possibly easiest way of signing up is through Github. The Arctica Project's GitLab site allows automatic account registration via Github's OpenID service.

Simply follow the /Sign in with <Github-Logo>/ link under the [site's login box](https://git.arctica-project.org).

## Contacting the Arctica GitLab site's maintainers

Once you have signed up with our GitLab site, you are logged out again, as one of the Arctica GitLab maintainers has to activate your account.

For that to happen, please send an e-Mail to our [developer's mailing list](https://lists.arctica-project.org/listinfo/devs) and introduce yourself and let us know why you want to have authenticated access to our GitLab site.

## Cloning Repositories

Once your account has been activated, please upload an SSH public key of yours into your user profile. Once that's done, you can clone hosted Git repositories via SSH.

The generic syntax for Git cloning is this:

```
$ git clone git@git.arctica-project.org:<group>/<git-project>.git
```

So, for example, the ``build.git`` repositories in the nx-X11-rebase group can be cloned like this:

```
$ git clone git@git.arctica-project.org:nx-X11-rebase/build.git
```

We are looking forward to your participation. In whatever that may be.