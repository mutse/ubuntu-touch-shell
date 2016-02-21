# ubuntu-touch-shell

Some Shell Commands Tips of Ubuntu Touch.

## How to Make Ubuntu Touch Image Writable

    $ adb shell
    $ sudo touch /userdata/.writable_image
    $ sudo reboot

## How to Import & Export Contacts

    $ syncevolution --import /home/phablet/Documents/utouch.vcf backend=evolution-contacts
    $ syncevolution --export /home/phablet/Documents/utcontacts.vcf backend=evolution-contacts

## How to Sending SMS from Shell

    $ /usr/share/ofono/scripts/send-sms /ril_0 +86134xxxxxxxx "Hello, I am Mutse Young and use ubuntu phone to send SMS to you." 0


