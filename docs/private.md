# Private Repositories

If you, during the launch of **Rocketdoo** decide to use a private repository, and you tell the launcher that
and indicate it to the launcher.

You will need to consider the following guidelines:

## Why use a Private Repository?

This function is for the developments that you or your company have destined for a particular client or for commercial
in particular or intended to be commercialized.

We know that if a development is intended to be commercialized, it is necessary that in our
GitHub repository, it must be private.

So what this functionality does, is to read in the directory of your system user,
look for the hidden folder *.ssh/* and show on screen the SSH keys that you have in that location.
For this it is necessary that previously you in addition to have created one or more keys
SSH keys are configured as access keys in your *GitHub* account.

Once **Rocketdoo** has read and displayed the SSH keys you have,
you will be the one to decide which key to use.

Rocketdoo will list and enumerate all the SSH keys you have and you will be able to decide
which key to use based on the number that corresponds to your key.

## My SSH keys, are they secure?

As we know, SSH keys are an encrypted tool that allows us to connect remotely to our repository,
and therefore they provide security when working with private repositories.

Faced with this reality, it is important for the developer to know that his keys are secure in our automated development environment,
*Rocketdoo* is only in charge of mapping your SSH key only within the Odoo development container (in the web container),
which, as we know, in the first instance its development environment is local and moreover each container is ephemeral,
therefore all the information inside each container will be ephemeral and removable if you wish.

Also this content is not mapped in git, so when you commit and push,
when you commit and push, this information will not travel to your remote repository.

Finally, if you choose to use a private repository, when you finish the launcher of our *Rocketdoo* environment,
you will see that in your development directory, a *.ssh/* folder has been created where the selected key will be stored.