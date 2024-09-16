# BUILDH3R_Aleo_task

Deployment: at1x36rgqjtvlv0n2u2s2u3gjvvpwx58yhqtyvd7wv7n6wvxv9ycgrs5dwr6e ('auction_dapp.aleo')

Aleo wallet: aleo1mykpp07zqpedx2es9prjnwstu9a9a7gxe7nrp560qg3auaepng9qvcehjx


<img width="1317" alt="image" src="https://github.com/user-attachments/assets/d6d1462c-83bf-48de-9363-181cfabd2664">


Scan screen

<img width="1330" alt="image" src="https://github.com/user-attachments/assets/bbc58885-dc94-4c5e-83e1-0a45659dc251">


Function code <claim> done


    transition claim(bid: Bid) -> Prize {
        assert_eq(bid.is_winner, true);
        return Prize {
            owner: bid.bidder,
            amount: bid.amount,
        };
