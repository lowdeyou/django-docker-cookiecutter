FROM mailhog/mailhog:v1.0.1

ENV MH_STORAGE maildir
ENV MH_MAILDIR_PATH /home/mailhog/mails

RUN mkdir -p /home/mailhog/mails

ENTRYPOINT ["/bin/sh", "-c", "MailHog &>/dev/null"]