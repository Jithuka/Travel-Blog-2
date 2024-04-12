# Travel-Blog-2

import React from 'react';
import { makeStyles } from '@material-ui/core/styles';
import {
  Container,
  Typography,
} from '@material-ui/core';

const useStyles = makeStyles((theme) => ({
  root: {
    marginTop: theme.spacing(4),
  },
}));

const BeijingPage = () => {
  const classes = useStyles();

  return (
    <div className={classes.root}>
      <Container>
        <Typography variant="h4" gutterBottom>Beijing</Typography>
        <Typography variant="body1">
          Beijing, China’s sprawling capital, has history stretching back 3 millennia. Yet it’s known as much for modern architecture as its ancient sites such as the grand Forbidden City complex, the imperial palace during the Ming and Qing dynasties.
        </Typography>
        {/* Add more information, images, etc. */}
      </Container>
    </div>
  );
};

export default BeijingPage;
